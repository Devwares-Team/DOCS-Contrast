---
title: "DataTable"
metaTitle: "Angular Bootstrap DataTable"
metaDescription: "Angular Bootstrap DataTables are components that mix tables with advanced options like searching, sorting and pagination"

---

# Angular Bootstrap DataTables

Angular Bootstrap DataTables are components that mix tables with advanced options like searching, sorting and pagination.

## Default DataTable

In this tutorial we use the [CDBCard](https://www.devwares.com/docs/contrast/angular/components/card) component for the table body. Check out the docs for more understanding.  

![Angular Bootstrap Datatables Default](./images/datatable.png)

###### html
```html
<CDBCard style="margin: 1rem;">
  <CDBCardBody>
    <div class="container">
      <div class="row">
        <div class="col-md-6 mx-auto pl-0">
          <label>
              Show Entries
              <select class='custom-select custom-select-sm form-control form-control-sm ml-0'
                  style="margin-left: .5rem" (change)='changeEntries($event)'>
                  <option *ngFor='let entry of entries' [value]="entry" [key]='entry'>
                      {{ entry }}
                  </option>
              </select>
          </label>
        </div>
        <div class="col-md-6 mx-auto pl-0 pr-0 mb-1">
          <div class="md-form">
            <input type="text" placeholder="Search" class="form-control" [(ngModel)]="searchText" (keyup)="searchItems()" id="search-input">
          </div>
        </div>
        <table CdbTable CdbTableScroll scrollY="true" maxHeight="500" #tableEl1="CdbTable" stickyHeader="true" hover="true" striped='true' bordered="true" class="z-depth-1 col-md-12">
          <thead class="sticky-top">
          <tr>
            <th *ngFor="let head of headElements; let i = index" (sortEnd)="sort()" [CdbTableSort]="elements" [tableEl]='tableEl1' [enableSort]='headElements[i].enableSort' [sortBy]="headElements[i].field"
                scope="col">{{head.label | titlecase}} <mdb-icon fas icon="sort"></mdb-icon>
            </th>
          </tr>
          </thead>
          <tbody #row>
          <tr  *ngFor="let el of pages[activePage]; let i = index">
            <th  scope="row">{{el.name}}</th>
            <td  class="red-text">{{el.position}}</td>
            <td >{{el.office}}</td>
            <td >{{el.age}}</td>
            <td >{{el.date}}</td>
            <td >{{el.salary}}</td>
          </tr>
          <tr  *ngIf="!pages[activePage]">
            <td scope="row" colspan="100%">No Matching Records Found</td>
          </tr>
          </tbody>
        <thead class="sticky-top">
            <tr>
                <th *ngFor="let head of headElements; let i = index" [mdbTableSort]="elements" [sortBy]="headElements[i].field"
                    scope="col">{{head.label | titlecase}} <mdb-icon fas icon="sort"></mdb-icon>
                </th>
            </tr>
        </thead>
        </table>
        <div class="mt-2">
          Showing {{activePage > 0 ? (activePage * pages[0].length) + 1 : activePage + 1}} to {{pages.length - 1 > activePage
          ? pages[activePage].length * (activePage + 1)
          : elements.length}} of {{elements.length}} records
        </div>
        <CDBTable-pagination class="ml-auto pr-0 mt-2" [tableEl]='tableEl1' ></CDBTable-pagination>
      </div>
    </div>
  </CDBCardBody>
</CDBCard>
```
###### typescript
```typescript
import { Component, OnInit, ViewChild } from '@angular/core';
import {CdbTableDirective} from './/directives/cdb-table.directive'
@Component({
  selector: 'app-datatable',
  templateUrl: './datatable.component.html',
  styleUrls: ['./datatable.component.scss']
})
export class DatatableComponent implements OnInit {
  @ViewChild(CdbTableDirective, { static: true }) CdbTable: CdbTableDirective;
  elements: any = [
      {
        name: "Tiger Nixon",
        position: "System Architect",
        office: "Edinburgh",
        age: "61",
        date: "2011/04/25",
        salary: "$320",
      },
      {
        name: "Garrett Winters",
        position: "Accountant",
        office: "Tokyo",
        age: "63",
        date: "2011/07/25",
        salary: "$170",
      },
      {
        name: "Ashton Cox",
        position: "Junior Technical Author",
        office: "San Francisco",
        age: "66",
        date: "2009/01/12",
        salary: "$86",
      },
      {
        name: "Cedric Kelly",
        position: "Senior Javascript Developer",
        office: "Edinburgh",
        age: "22",
        date: "2012/03/29",
        salary: "$433",
      },
      {
        name: "Airi Satou",
        position: "Accountant",
        office: "Tokyo",
        age: "33",
        date: "2008/11/28",
        salary: "$162",
      },
      {
        name: "Brielle Williamson",
        position: "Integration Specialist",
        office: "New York",
        age: "61",
        date: "2012/12/02",
        salary: "$372",
      },
      {
        name: "Herrod Chandler",
        position: "Sales Assistant",
        office: "San Francisco",
        age: "59",
        date: "2012/08/06",
        salary: "$137",
      },
      {
        name: "Rhona Davidson",
        position: "Integration Specialist",
        office: "Tokyo",
        age: "55",
        date: "2010/10/14",
        salary: "$327",
      },
      {
        name: "Colleen Hurst",
        position: "Javascript Developer",
        office: "San Francisco",
        age: "39",
        date: "2009/09/15",
        salary: "$205",
      },
      {
        name: "Sonya Frost",
        position: "Software Engineer",
        office: "Edinburgh",
        age: "23",
        date: "2008/12/13",
        salary: "$103",
      },
      {
        name: "Jena Gaines",
        position: "Office Manager",
        office: "London",
        age: "30",
        date: "2008/12/19",
        salary: "$90",
      },
      {
        name: "Quinn Flynn",
        position: "Support Lead",
        office: "Edinburgh",
        age: "22",
        date: "2013/03/03",
        salary: "$342",
      },
      {
        name: "Charde Marshall",
        position: "Regional Director",
        office: "San Francisco",
        age: "36",
        date: "2008/10/16",
        salary: "$470",
      },
      {
        name: "Haley Kennedy",
        position: "Senior Marketing Designer",
        office: "London",
        age: "43",
        date: "2012/12/18",
        salary: "$313",
      },
      {
        name: "Tatyana Fitzpatrick",
        position: "Regional Director",
        office: "London",
        age: "19",
        date: "2010/03/17",
        salary: "$385",
      },
      {
        name: "Michael Silva",
        position: "Marketing Designer",
        office: "London",
        age: "66",
        date: "2012/11/27",
        salary: "$198",
      },
      {
        name: "Paul Byrd",
        position: "Chief Financial Officer (CFO)",
        office: "New York",
        age: "64",
        date: "2010/06/09",
        salary: "$725",
      },
      {
        name: "Gloria Little",
        position: "Systems Administrator",
        office: "New York",
        age: "59",
        date: "2009/04/10",
        salary: "$237",
      },
      {
        name: "Bradley Greer",
        position: "Software Engineer",
        office: "London",
        age: "41",
        date: "2012/10/13",
        salary: "$132",
      },
      {
        name: "Dai Rios",
        position: "Personnel Lead",
        office: "Edinburgh",
        age: "35",
        date: "2012/09/26",
        salary: "$217",
      },
      {
        name: "Jenette Caldwell",
        position: "Development Lead",
        office: "New York",
        age: "30",
        date: "2011/09/03",
        salary: "$345",
      },
      {
        name: "Yuri Berry",
        position: "Chief Marketing Officer (CMO)",
        office: "New York",
        age: "40",
        date: "2009/06/25",
        salary: "$675",
      },
      {
        name: "Caesar Vance",
        position: "Pre-Sales Support",
        office: "New York",
        age: "21",
        date: "2011/12/12",
        salary: "$106",
      },
      {
        name: "Doris Wilder",
        position: "Sales Assistant",
        office: "Sidney",
        age: "23",
        date: "2010/09/20",
        salary: "$85",
      },
      {
        name: "Angelica Ramos",
        position: "Chief Executive Officer (CEO)",
        office: "London",
        age: "47",
        date: "2009/10/09",
        salary: "$1",
      },
      {
        name: "Gavin Joyce",
        position: "Developer",
        office: "Edinburgh",
        age: "42",
        date: "2010/12/22",
        salary: "$92",
      },
      {
        name: "Jennifer Chang",
        position: "Regional Director",
        office: "Singapore",
        age: "28",
        date: "2010/11/14",
        salary: "$357",
      },
      {
        name: "Brenden Wagner",
        position: "Software Engineer",
        office: "San Francisco",
        age: "28",
        date: "2011/06/07",
        salary: "$206",
      },
      {
        name: "Fiona Green",
        position: "Chief Operating Officer (COO)",
        office: "San Francisco",
        age: "48",
        date: "2010/03/11",
        salary: "$850",
      },
      {
        name: "Shou Itou",
        position: "Regional Marketing",
        office: "Tokyo",
        age: "20",
        date: "2011/08/14",
        salary: "$163",
      },
      {
        name: "Michelle House",
        position: "Integration Specialist",
        office: "Sidney",
        age: "37",
        date: "2011/06/02",
        salary: "$95",
      },
      {
        name: "Suki Burks",
        position: "Developer",
        office: "London",
        age: "53",
        date: "2009/10/22",
        salary: "$114",
      },
      {
        name: "Prescott Bartlett",
        position: "Technical Author",
        office: "London",
        age: "27",
        date: "2011/05/07",
        salary: "$145",
      },

      {
        name: "Donna Snider",
        position: "Customer Support",
        office: "New York",
        age: "27",
        date: "2011/01/25",
        salary: "$112",
      },
  ];
  pages = []
  activePage = 0;
  previousData;

  //Declare entries options
  entries = [5, 10, 15]
  //table head elements
  headElements = [
    {
      label: "Name",
      field: "name",
      enableSort: "enabled",
    },
    {
      label: "Position",
      field: "position",
      enableSort: "enabled",
    },
    {
      label: "Office",
      field: "office",
      enableSort: "enabled",
    },
    {
      label: "Age",
      field: "age",
      enableSort: "enabled",
    },
    {
      label: "Date",
      field: "date",
      enableSort: "disabled",
    },
    {
      label: "Salary",
      field: "salary",
      enableSort: "disabled",
    },
  ];

  searchText: string = '';

  constructor() { }

  ngOnInit(): void {
    //subscribe to the current active page
    this.CdbTable._activePage.subscribe(data => {
      this.activePage = data
    })

    this.CdbTable.setEntries(this.entries[0])
    this.CdbTable.setDataSource(this.elements)
    this.CdbTable.setPages()
    this.previousData = this.CdbTable.getDataSource();
    this.pages = this.CdbTable.pages
  }

  searchItems() {
    const prev = this.CdbTable.getDataSource();

    if (!this.searchText) {
      this.elements = this.CdbTable.getDataSource();
      this.CdbTable.setDataSource(this.previousData);
      this.CdbTable.setPages()
      this.pages = this.CdbTable.pages
    }

    if (this.searchText) {
      this.CdbTable.setDataSource(this.previousData);
      this.elements = this.CdbTable.filterData(this.searchText);
      this.CdbTable.setDataSource(this.elements)
      this.CdbTable.setPages()
      this.pages = this.CdbTable.pages
    }
  }

  changeEntries(e) {
    this.CdbTable.setEntries(e.target.value)
    this.CdbTable.setPages()
    this.pages = this.CdbTable.pages
    this.CdbTable._activePage.next(0)
  }
  sort() {
    this.pages = this.CdbTable.pages
  }
}
```


