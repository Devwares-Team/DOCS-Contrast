---
title: "Modal"
metaTitle: "Angular Bootstrap Modal component"
metaDescription: "Angular Bootstrap Modal is lightweight, but powerful & multifunctional popup"
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/angular/components/modal.md"
---

# Contrast Angular Bootstrap Modal

Contrast Angular Bootstrap Modal is a lightweight, but powerful & multifunctional popup. 

It is a dialog box/popup window which can be used for light boxes, user notifications, UI enhancements, e-commerce components and many other cases.

It can easily be customized, you can configure the size, position, and content of this component. Below are several variants of the Modal component, created by configuring the size, styles and position.

## Importing the Contrast Angular Bootstrap Modal Module

To use the Contrast Angular Bootstrap Modal component in your project you need to import `ModalModule`.


## Custom Modal

![Angular Bootstrap Custom Modal](https://imgur.com/z99wzWH.gif)

###### HTML
```html
<CDBBtn (click)="modal1.toggleModal()" color="dark">
    Modal
</CDBBtn>
<CDBModal #modal1="cdbModal" [centered]=true>
    <CDBCard>
        <CDBCardImage class="img-fluid" src="/assets/img/modal.jpg"></CDBCardImage>
        <CDBCardBody>
            <CDBCardTitle>Title</CDBCardTitle>
            <CDBCardText>
                Proin ut dui sed metus pharetra hend rerit vel non mi. Nulla
                orcane faucibus ex, non facilisis nisl. Maexenas aliquet
                mauris ut tempus. Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aspernatur iste
                officiis porro hic corrupti laborum voluptatem ratione exercitationem voluptates amet accusamus
                accusantium rerum consequuntur deserunt vero eius, ipsa repellat. Voluptate explicabo deleniti
                laudantium accusantium minima laborum voluptatibus ipsam sapiente quo! Aliquid aspernatur
                facilis quos recusandae eius porro expedita minima molestias, eaque nobis omnis unde sint, alias
                ipsa dicta non voluptatibus doloremque quod ad cumque, consequatur soluta. Vitae soluta
                doloribus cumque iste nesciunt. Veniam eum deserunt placeat veritatis, aspernatur aperiam amet
                exercitationem fugiat ullam voluptatem nostrum rem impedit doloremque magni voluptate sunt
                asperiores aliquam excepturi unde ipsam possimus! Optio sapiente aut et blanditiis repellendus
                nulla numquam voluptatem excepturi, consequuntur pariatur. Quo suscipit harum magnam excepturi
                magni nulla, quasi eos iste. Laboriosam quisquam eaque omnis inventore at obcaecati nemo
                possimus animi asperiores ducimus, fugiat velit, hic, molestiae numquam. Repellendus, cumque!
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut adipisci blanditiis obcaecati
                temporibus dolorum dignissimos officia perferendis id quis ratione delectus pariatur odio
                repudiandae alias modi, vitae voluptatem fugiat beatae neque accusamus corrupti! A vero optio
                totam suscipit. Delectus quaerat repellat dolores adipisci earum a at cumque cupiditate sit
                eaque.
            </CDBCardText>
            <div class="d-flex">
                <div class="d-flex justify-content-start" style="flex: 50%">
                    <CDBBtn color="light" [flat]=true>
                        Label
                    </CDBBtn>
                </div>
                <div class="d-flex justify-content-end" style="flex: 50%">
                    <CDBBtn color="white" [flat]=true (click)="modal1.toggleModal()">
                        Cancel
                    </CDBBtn>
                    <CDBBtn color="dark" [flat]=true (click)="modal1.toggleModal()">
                        Done
                    </CDBBtn>
                </div>
            </div>
        </CDBCardBody>
    </CDBCard>
</CDBModal>
```

## Modal Sizes

![Angular Bootstrap Modal Sizes](https://imgur.com/h8y6UlS.gif)

###### HTML
```html
<CDBBtn color="light" [flat]=true (click)="modal2.toggleModal()">
    Medium modal
</CDBBtn>
<CDBModal #modal2="cdbModal">
    <CDBCard [border]=true>
        <CDBCardImage class="img-fluid" src="/assets/img/modal.jpg"></CDBCardImage>
        <CDBCardBody>
            <CDBCardTitle>Title</CDBCardTitle>
            <CDBCardText>
                Proin ut dui sed metus pharetra hend rerit vel non mi. Nulla
                orcane faucibus ex, non facilisis nisl. Maexenas aliquet
                mauris ut tempus.
            </CDBCardText>
            <div class="d-flex">
                <div class="d-flex justify-content-start" style="flex: 50%">
                    <CDBBtn color="light" [flat]=true>
                        Label
                    </CDBBtn>
                </div>
                <div class="d-flex justify-content-end" style="flex: 50%">
                    <CDBBtn color="white" [flat]=true (click)="modal2.toggleModal()">
                        Cancel
                    </CDBBtn>
                    <CDBBtn color="dark" [flat]=true (click)="modal2.toggleModal()">
                        Done
                    </CDBBtn>
                </div>
            </div>
        </CDBCardBody>
    </CDBCard>
</CDBModal>
<CDBBtn color="light" [flat]=true (click)="modal3.toggleModal()">
    Small modal
</CDBBtn>
<CDBModal #modal3="cdbModal" size="sm">
    <CDBCard>
        <CDBCardImage class="img-fluid" src="/assets/img/modal.jpg"></CDBCardImage>
        <CDBCardBody>
            <CDBCardTitle>Title</CDBCardTitle>
            <CDBCardText>
                Proin ut dui sed metus pharetra hend rerit vel non mi. Nulla
                orcane faucibus ex, non facilisis nisl. Maexenas aliquet
                mauris ut tempus.
            </CDBCardText>
            <div class="d-flex">
                <div class="d-flex justify-content-start" style="flex: 50%">
                    <CDBBtn color="light" [flat]=true>
                        Label
                    </CDBBtn>
                </div>
                <div class="d-flex justify-content-end" style="flex: 50%">
                    <CDBBtn color="white" [flat]=true (click)="modal3.toggleModal()">
                        Cancel
                    </CDBBtn>
                    <CDBBtn color="dark" [flat]=true (click)="modal3.toggleModal()">
                        Done
                    </CDBBtn>
                </div>
            </div>
        </CDBCardBody>
    </CDBCard>
</CDBModal>
<CDBBtn color="light" [flat]=true (click)="modal4.toggleModal()">
    Large modal
</CDBBtn>
<CDBModal #modal4="cdbModal" size="lg">
    <CDBCard [border]=true>
        <CDBCardBody>
            <CDBCardTitle>Title</CDBCardTitle>
            <CDBCardText>
                Proin ut dui sed metus pharetra hend rerit vel non mi. Nulla
                orcane faucibus ex, non facilisis nisl. Maexenas aliquet
                mauris ut tempus.
            </CDBCardText>
            <div class="d-flex">
                <div class="d-flex justify-content-start" style="flex: 50%">
                    <CDBBtn color="light" [flat]=true>
                        Label
                    </CDBBtn>
                </div>
                <div class="d-flex justify-content-end" style="flex: 50%">
                    <CDBBtn color="white" [flat]=true (click)="modal4.toggleModal()">
                        Cancel
                    </CDBBtn>
                    <CDBBtn color="dark" [flat]=true (click)="modal4.toggleModal()">
                        Done
                    </CDBBtn>
                </div>
            </div>
        </CDBCardBody>
    </CDBCard>
</CDBModal>
<CDBBtn color="light" [flat]=true (click)="modal5.toggleModal()">
    Fluid modal
</CDBBtn>
<CDBModal #modal5="cdbModal" size="fluid">
    <CDBCard [border]=true>
        <CDBCardBody>
            <CDBCardTitle>Title</CDBCardTitle>
            <CDBCardText>
                Proin ut dui sed metus pharetra hend rerit vel non mi. Nulla
                orcane faucibus ex, non facilisis nisl. Maexenas aliquet
                mauris ut tempus.
            </CDBCardText>
            <div class="d-flex">
                <div class="d-flex justify-content-start" style="flex: 50%">
                    <CDBBtn color="light" [flat]=true>
                        Label
                    </CDBBtn>
                </div>
                <div class="d-flex justify-content-end" style="flex: 50%">
                    <CDBBtn color="white" [flat]=true (click)="modal5.toggleModal()">
                        Cancel
                    </CDBBtn>
                    <CDBBtn color="dark" [flat]=true (click)="modal5.toggleModal()">
                        Done
                    </CDBBtn>
                </div>
            </div>
        </CDBCardBody>
    </CDBCard>
</CDBModal>
```

## Modal Positions

![Angular Bootstrap Modal Positions ](https://imgur.com/sT4ZwEV.gif)

###### HTML
```html
<CDBBtn color="dark" [flat]=true (click)="modal6.toggleModal()">
    Top right
</CDBBtn>
<CDBModal #modal6="cdbModal" position="top-right">
    <CDBModalHeader [toggle]="modal6">Title</CDBModalHeader>
    <CDBModalBody>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
        eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
        enim ad minim veniam, quis nostrud exercitation ullamco laboris
        nisi ut aliquip ex ea commodo consequat.
    </CDBModalBody>
    <CDBModalFooter>
        <CDBBtn color="dark" [flat]=true (click)="modal6.toggleModal()">
            Close
        </CDBBtn>
        <CDBBtn color="light" [flat]=true (click)="modal6.toggleModal()">
            Save changes
        </CDBBtn>
    </CDBModalFooter>
</CDBModal>
<CDBBtn color="dark" [flat]=true (click)="modal7.toggleModal()">
    Bottom left
</CDBBtn>
<CDBModal #modal7="cdbModal" position="bottom-left">
    <CDBModalHeader [toggle]="modal7">Title</CDBModalHeader>
    <CDBModalBody>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
        eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
        enim ad minim veniam, quis nostrud exercitation ullamco laboris
        nisi ut aliquip ex ea commodo consequat.
    </CDBModalBody>
    <CDBModalFooter>
        <CDBBtn color="dark" [flat]=true (click)="modal7.toggleModal()">
            Close
        </CDBBtn>
        <CDBBtn color="light" [flat]=true (click)="modal7.toggleModal()">
            Save changes
        </CDBBtn>
    </CDBModalFooter>
</CDBModal>
<CDBBtn color="dark" [flat]=true (click)="modal8.toggleModal()">
    Top Left
</CDBBtn>
<CDBModal #modal8="cdbModal" position="top-left">
    <CDBModalHeader [toggle]="modal8">Title</CDBModalHeader>
    <CDBModalBody>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
        eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
        enim ad minim veniam, quis nostrud exercitation ullamco laboris
        nisi ut aliquip ex ea commodo consequat.
    </CDBModalBody>
    <CDBModalFooter>
        <CDBBtn color="dark" [flat]=true (click)="modal8.toggleModal()">
            Close
        </CDBBtn>
        <CDBBtn color="light" [flat]=true (click)="modal8.toggleModal()">
            Save changes
        </CDBBtn>
    </CDBModalFooter>
</CDBModal>
<CDBBtn color="light" [flat]=true (click)="modal9.toggleModal()">
    Bottom right
</CDBBtn>
<CDBModal #modal9="cdbModal" position="bottom-right">
    <CDBModalHeader [toggle]="modal9">Title</CDBModalHeader>
    <CDBModalBody>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
        eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
        enim ad minim veniam, quis nostrud exercitation ullamco laboris
        nisi ut aliquip ex ea commodo consequat.
    </CDBModalBody>
    <CDBModalFooter>
        <CDBBtn color="dark" (click)="modal9.toggleModal()">
            Close
        </CDBBtn>
        <CDBBtn color="light" [flat]=true (click)="modal9.toggleModal()">
            Save changes
        </CDBBtn>
    </CDBModalFooter>
</CDBModal>
<CDBBtn color="light" [flat]=true (click)="modal10.toggleModal()">
    Center
</CDBBtn>
<CDBModal #modal10="cdbModal">
    <CDBModalHeader [toggle]="modal10">Title</CDBModalHeader>
    <CDBModalBody>
        Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
        eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
        enim ad minim veniam, quis nostrud exercitation ullamco laboris
        nisi ut aliquip ex ea commodo consequat.
    </CDBModalBody>
    <CDBModalFooter>
        <CDBBtn color="dark" (click)="modal10.toggleModal()">
            Close
        </CDBBtn>
        <CDBBtn color="light" [flat]=true (click)="modal10.toggleModal()">
            Save changes
        </CDBBtn>
    </CDBModalFooter>
</CDBModal>
```

## API Reference: Contrast Angular Bootstrap Modal Props

This section will build on your information about the props you get to use with the Contrast Angular Bootstrap Modal component. You will find out what these props do, their default values, and how you would use them in your code.

The table below lists other prop options of the `CDBModal`.

| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
| class      | String       |              |Adds custom modal-content classes	      |     class="myClass" |
| wrapperClass      | String       |              |Adds custom class to wrapper container      |     wrapperClass="myClass" |
| modalClass      | String       |              |Adds custom modal-dialog element	      |     modalClass="myClass" |
| contentClass      | String       |              |Adds custom modal-content classes	      |     contentClass="myClass" |
| backdropClass      | String       |              |Adds custom class to modal-backdrop element	      |     backdropClass="myClass" |
| disableBackdrop        | Boolean      | false        |  	Disable backdrop if this prop is true. | disableBackdrop=true |
| animation         | String       |           | Changes direction of animation. Choose from `top` / `bottom` / `right` / `left`. | animation="bottom" |
| autoFocus        | Boolean      | true        |  	Defines if modal should receive focus | autoFocus=false |
| backdrop        | Boolean      | true        |   	If false, the backdrop is not rendered.	| backdrop=false |
| cascading        | Boolean      | false        |  	Adds cascading-class to modal-dialog element | cascading=true |
| centered        | Boolean      | false        | Add custom class to modal-dialog element 	| centered=true |
| disableFocusTrap        | Boolean      | true        |  If true, removes focus trap effect. 	| disableFocusTrap=false |
| fade        | Boolean      | true        | Removes transition | fade=false |
| frame        | Boolean      | false        |  	Changes the position of the modal. It has to be used along with position prop equal to `bottom` / `top` | frame=true position="bottom" |
| fullHeight    | Boolean      | false        |  	Changes the position of the modal. It has to be used along with position prop equal to `bottom` / `top` | fullHeight=true position="bottom" |
| isOpen        | Boolean      | true        |  If true, removes focus trap effect. 	| isOpen=Modal |
| keyboard        | Boolean      | true        | Closes the modal when the escape key is pressed. | keyboard=false |
| labelledBy      | String       |              | Changes aria-labelledby attribute  |     labelledBy="myLabel" |
| modalStyle      | String       |              | Predefines modal style. Choose one of success / `info` / `danger` / `warning`.  |     modalStyle="warning" |
| position      | String       |              |  	Changes the position of the modal |     position="top-right" |
| side        | Boolean      | false        |  	Changes the position of the modal. It has to be used along with position prop equal to `bottom-right`/`bottom-left`/`top-right`/`top-left`| side=true position="bottom-left" |
| size      | String       |              |  	Changes the size of the modal. Choose from `sm` / `lg` / `fluid` |     size="fluid" |
| toggle      | function       |              |  Defines function which fires on close/open event	|     toggle=myFunction |
| hiddenModal      | function       |              |   	This event is fired after the modal is closed.	|     hiddenModal=myFunction |
| hideModal      | function       |              |   	This event is fired just before the modal is hidden. 	|     hideModal=myFunction |
| showModal      | function       |              |    	This event is fired just before the modal is open.	|     showModal=myFunction |

## API Reference: Contrast Modal Body Properties

The table below shows the configuration options of the CDBModalBody component.

| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
| class| String       |              |Adds custom class ModalBody component      |     class="myClass" |

## API Reference: Contrast Modal Footer Properties

The table below shows the configuration options of the CDBModalFooter component.

| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
| class| String       |              |Adds custom class ModalFooter component      |     class="myClass" |

## API Reference: Contrast Modal Header Properties

The table below shows the configuration options of the CDBModalHeader component.

| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
| class| String       |              |Adds custom class ModalHeader component      |     class="myClass" |
| titleClass      | String       |              | Adds custom class to title element. |     titleClass="myTitleClass" |
| closeArialLabel      | String       |    Close          |  	Defines custom label for close button      |     closeArialLabel="myClass" |
| toggle      | function       |              |  Defines function which fires on close/open event	|     toggle=myFunction |
