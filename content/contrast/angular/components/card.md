---
title: "Card"
metaTitle: "Angular Bootstrap Card Component"
metaDescription: "Angular Bootstrap card is a flexible and extensible content container"
githubUrl: "https://github.com/Devwares-Team/DOCS-Contrast/blob/master/content/contrast/angular/components/card.md"
---

# Contrast Angular Bootstrap Card

 Contrast  Angular Bootstrap card is a flexible and configurable content container. It includes several headers and footers options, a wide variety of content, contextual background colors, and powerful display options.
Card components display content build of different elements with characteristic shadows, depth and hover effects.

## Importing the Contrast Angular Bootstrap Card Module

To use the Contrast Angular Bootstrap Card component in your project you need to import `CardModule`.

```ts
import {CardModule } from 'cdbangular';
```

## Default Card

Contrast Angular Bootstrap Cards are built with as little markup and styles as possible, but still manage to deliver a ton of control and customization.

Alongside the `CDBCard` component other components we use to create our card are the `CDBCardImage` component for holding images in our card, the `CDBCardBody` for the body of the card, the `CDBCardTitle` component, which is for writing titles, and `CDBCardText` for texts in our card.

![Angular Bootstrap Card Default](./images/cardsbasic.png)

###### HTML
```html
<CDBCard style="width: 25rem">
    <CDBCardImage class="img-fluid" src="https://cdn.pixabay.com/photo/2015/04/23/22/00/tree-736885__340.jpg">
    </CDBCardImage>
    <CDBCardBody>
        <CDBCardTitle>Basic</CDBCardTitle>
        <CDBCardText>This is just a card text Get important notifications about you or activity you've missed
        </CDBCardText>
        <CDBBtn class="mt-3">
            Button
        </CDBBtn>
    </CDBCardBody>
</CDBCard>
```
## Simple Cards

![Angular Bootstrap Card Simple](./images/cardsimple.png)

###### HTML
```html
<CDBCard style="width: 25rem">
    <CDBCardBody>
        <CDBCardTitle>Heading</CDBCardTitle>
        <CDBCardText>Paragraph</CDBCardText>
        <div class="d-flex justify-content-center">
            <CDBBtn class="mt-3" color="light" [flat]=true [circle]=true>
                Button
            </CDBBtn>
        </div>
    </CDBCardBody>
</CDBCard>
<CDBCard style="width: 25rem">
    <CDBCardBody>
        <CDBCardTitle>Heading</CDBCardTitle>
        <CDBCardText>Paragraph</CDBCardText>
        <CDBBtn class="mt-3" color="light" [flat]=true [block]=true>
            Button
        </CDBBtn>
    </CDBCardBody>
</CDBCard>
<CDBCard style="width: 25rem">
    <CDBCardBody>
        <CDBCardTitle>Heading</CDBCardTitle>
        <CDBCardText>Paragraph</CDBCardText>
        <CDBBtn class="mt-3" color="light" [flat]=true [circle]=true>
            Button
        </CDBBtn>
    </CDBCardBody>
</CDBCard>
```
## Bordered Cards

Set the [border] property to true to give your cards borders.

![Angular Bootstrap Cards Bordered](./images/cardbodered.png)

###### HTML
```html
<CDBCard style="width: 25rem" [border]=true>
    <CDBCardBody>
        <CDBCardTitle>Heading</CDBCardTitle>
        <CDBCardText>Paragraph</CDBCardText>
        <div class="d-flex justify-content-center">
            <CDBBtn class="mt-3" color="light" [flat]=true [circle]=true>
                Button
            </CDBBtn>
        </div>
    </CDBCardBody>
</CDBCard>
<CDBCard style="width: 25rem" [border]=true>
    <CDBCardBody>
        <CDBCardTitle>Heading</CDBCardTitle>
        <CDBCardText>Paragraph</CDBCardText>
        <CDBBtn class="mt-3" color="light" [flat]=true [block]=true>
            Button
        </CDBBtn>
    </CDBCardBody>
</CDBCard>
<CDBCard style="width: 25rem">
    <CDBCardBody>
        <CDBCardTitle>Heading</CDBCardTitle>
        <CDBCardText>Paragraph</CDBCardText>
        <CDBBtn class="mt-3" color="light" [flat]=true [circle]=true>
            Button
        </CDBBtn>
    </CDBCardBody>
</CDBCard>
```
## Artwork Top Cards

![Angular Bootstrap Artwork Top Cards](./images/cardsartworktop.png)

###### HTML
```html
<CDBCard style="width: 25rem">
    <CDBCardImage class="img-fluid" src="https://cdn.pixabay.com/photo/2015/04/23/22/00/tree-736885__340.jpg">
    </CDBCardImage>
    <CDBCardBody>
        <CDBCardTitle>Heading</CDBCardTitle>
        <CDBCardText>Paragraph</CDBCardText>
        <div class="d-flex justify-content-center">
            <CDBBtn class="mt-3" color="light" [flat]=true [block]=true [circle]=true>
                Button
            </CDBBtn>
        </div>
    </CDBCardBody>
</CDBCard>
<CDBCard style="width: 25rem" [border]=true>
    <CDBCardImage class="img-fluid" src="https://cdn.pixabay.com/photo/2015/04/23/22/00/tree-736885__340.jpg">
    </CDBCardImage>
    <CDBCardBody>
        <CDBCardTitle>Heading</CDBCardTitle>
        <CDBCardText>Paragraph</CDBCardText>
        <CDBBtn class="mt-3" color="light" [flat]=true [circle]=true>
            Button
        </CDBBtn>
    </CDBCardBody>
</CDBCard>
```
## Artwork Middle Cards

![Angular Bootstrap Middle Cards](./images/cardsartworkmiddle.png)

###### HTML
```html
<CDBCard style="width: 25rem">
    <CDBCardBody>
        <CDBCardTitle>Heading</CDBCardTitle>
        <CDBCardText>Paragraph</CDBCardText>
    </CDBCardBody>
    <CDBView>
        <CDBIframe src="https://www.youtube.com/embed/xnczyP2jSR0"></CDBIframe>
    </CDBView>
    <CDBCardBody>
        <CDBBtn color="light" [flat]=true [circle]=true>
            Button
        </CDBBtn>
    </CDBCardBody>
</CDBCard>
<CDBCard style="width: 25rem" [border]=true>
    <CDBCardBody>
        <CDBCardTitle>Heading</CDBCardTitle>
        <CDBCardText>Paragraph</CDBCardText>
    </CDBCardBody>
    <CDBView>
        <CDBIframe src="https://www.youtube.com/embed/xnczyP2jSR0"></CDBIframe>
    </CDBView>
    <CDBCardBody>
        <CDBBtn color="light" [flat]=true [circle]=true>
            Button
        </CDBBtn>
    </CDBCardBody>
</CDBCard>
```



## Widget Cards


![Angular Bootstrap Widget Cards](./images/cardwidget.png)

###### HTML
```html
<CDBCard style="width: 25rem">
    <CDBCardBody>
        <CDBCardTitle class="lead">Total Downloads</CDBCardTitle>
        <CDBCardTitle tag="h2">1,057,891</CDBCardTitle>
        <CDBCardText [small]=true [muted]=true>Oct 1 - Dec 31,
            <CDBIcon [fas]=true icon="globe"></CDBIcon> Worldwide</CDBCardText>
    </CDBCardBody>
</CDBCard>
```


## Profile Display Card

![Angular Bootstrap Profile Display Card](./images/cardprofiledisplay.png)

###### HTML
```html
<CDBCard style="width: 25rem">
    <CDBCardImage class="img-fluid" src="https://cdn.pixabay.com/photo/2015/04/23/22/00/tree-736885__340.jpg">
    </CDBCardImage>
    <div class="mx-auto">
        <CDBPaneImage style="margin-top: -5rem" width="130px"
            src="https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcQ7ntUU7AzmOxa5HB8zS83sa-JFHEfZJAoI2A&usqp=CAU">
        </CDBPaneImage>
    </div>
    <CDBCardBody class="d-flex flex-column align-items-center mb-4">
        <CDBCardTitle>Sam Russo</CDBCardTitle>
        <CDBCardText>Senior Software Developer</CDBCardText>
        <CDBCardText class="text-muted">Detroit, USA</CDBCardText>
        <div class="mt-3">
            <CDBBtn size="small" color="dark">
                <CDBIcon [fas]=true icon="user-plus"></CDBIcon> Connect
            </CDBBtn>
            <CDBBtn class="ml-3" size="small" color="warning"> Send Message </CDBBtn>
        </div>
    </CDBCardBody>
</CDBCard>
```


## Profile List Card


![Angular Bootstrap Profile List Card](./images/cardprofilelist.png)

###### HTML
```html
<CDBCard style="width: 25rem">
    <CDBCardTitle class="lead p-3 border-bottom">Team Members</CDBCardTitle>
    <CDBCardBody class="py-0">
        <CDBPane class="mt-2">
            <CDBPaneImage size="md"
                src="https://media.istockphoto.com/photos/beautiful-woman-wearing-brown-curly-hairstyle-picture-id495006065?s=170x170">
            </CDBPaneImage>

            <div class="ml-3">
                <CDBCardTitle class="my-0 h6">Warren Briggs</CDBCardTitle>
                <p class="small m-0">
                    <CDBIcon [fas]=true class="p-0 mr-1 text-success" icon="circle"></CDBIcon>
                    Online
                </p>
            </div>

            <div class="ml-auto">
                <CDBBtn style="width: 45px" size="small" color="success" [flat]=true>Add</CDBBtn>
            </div>
        </CDBPane>
        <CDBPane class="mt-4">
            <CDBPaneImage size="md"
                src="data:image/jpeg;base64,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">
            </CDBPaneImage>

            <div class="ml-3">
                <CDBCardTitle class="my-0 h6">Lu Chen</CDBCardTitle>
                <p class="small m-0">
                    <CDBIcon [fas]=true class="p-0 mr-1 text-warning" icon="circle"></CDBIcon>
                    In a meeting
                </p>
            </div>

            <div class="ml-auto">
                <CDBBtn style="width: 45px" size="small" color="success" [flat]=true>Add</CDBBtn>
            </div>
        </CDBPane>
        <CDBPane class="mt-4">
            <CDBPaneImage size="md"
                src="data:image/jpeg;base64,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">
            </CDBPaneImage>

            <div class="ml-3">
                <CDBCardTitle class="my-0 h6">Lilah Loselev</CDBCardTitle>
                <p class="small m-0">
                    <CDBIcon [fas]=true class="p-0 mr-1 text-muted" icon="circle">
                    </CDBIcon>
                    Not Available
                </p>
            </div>

            <div class="ml-auto">
                <CDBBtn style="width: 45px" size="small" color="success" [flat]=true>Add</CDBBtn>
            </div>
        </CDBPane>
        <CDBPane class="my-4">
            <CDBPaneImage size="md"
                src="data:image/jpeg;base64,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">
            </CDBPaneImage>

            <div class="ml-3">
                <CDBCardTitle class="my-0 h6">Danny</CDBCardTitle>
                <p class="small m-0">
                    <CDBIcon [fas]=true class="p-0 mr-1 text-danger" icon="circle">
                    </CDBIcon>
                    Offline
                </p>
            </div>

            <div class="ml-auto">
                <CDBBtn style="width: 45px" size="small" color="success" [flat]=true>Add</CDBBtn>
            </div>
        </CDBPane>
    </CDBCardBody>
</CDBCard>
```


## Artwork Full Cards



![Angular Bootstrap Artwork Full Cards](./images/cardartworkfull.png)

###### HTML
```html
<CDBCard
    style="width: 25rem; background-image: url('https://cdn.pixabay.com/photo/2018/08/14/13/23/ocean-3605547_960_720.jpg')">
    <CDBCardBody style="color: white">
        <CDBCardTitle>Heading</CDBCardTitle>
        <CDBCardText>Paragraph</CDBCardText>
    </CDBCardBody>
    <CDBCardBody>
        <CDBBtn color="white" [flat]=true [circle]=true>
            Button
        </CDBBtn>
    </CDBCardBody>
</CDBCard>
<CDBCard
    style="width: 25rem; background-image: url('https://cdn.pixabay.com/photo/2018/08/14/13/23/ocean-3605547_960_720.jpg')"
    [border]=true>
    <CDBCardBody style="color: white">
        <CDBCardTitle>Heading</CDBCardTitle>
        <CDBCardText>Paragraph</CDBCardText>
    </CDBCardBody>
    <CDBCardBody>
        <CDBBtn color="white" [flat]=true [circle]=true>
            Button
        </CDBBtn>
    </CDBCardBody>
</CDBCard>
```


## Profile Cards



![Angular Bootstrap Cards Profile](./images/cardprofile1.png)
![Angular Bootstrap Cards Profile](./images/cardprofile2.png)
![Angular Bootstrap Cards Profile](./images/cardprofile3.png)
![Angular Bootstrap Cards Profile](./images/cardprofile4.png)

###### HTML
```html
<CDBCard
    style="position: relative; width: 25rem; height: 33rem; padding: 25px; background-image: url(/assets/img/rectangle.png); background-repeat: no-repeat; background-position: center;">
    <CDBCardBody
        style="background-color: white; width: calc(100% - 50px); text-align: center; align-items: center; position: absolute; bottom: 25px">
        <CDBCardTitle style="color: #333333" class="font-weight-normal">Chukwudi Mezue</CDBCardTitle>
        <CDBCardText style="color: #333333; font-size: 0.9rem" class="font-weight-lighter">Product
            Designer
        </CDBCardText>
        <CDBCardText style="color: #333333" class="font-weight-light">Enugu, Nigeria</CDBCardText>
        <CDBCardBody style="display: flex; justify-content: space-between; padding: 0 50px; margin: 20px 0">
            <CDBIcon size="lg" [fab]=true icon="facebook-f" style="color: #333333"></CDBIcon>
            <CDBIcon size="lg" [fab]=true icon="twitter" style="color: #333333"></CDBIcon>
            <CDBIcon size="lg" [fab]=true icon="instagram" style="color: #333333"></CDBIcon>
        </CDBCardBody>
        <CDBBtn color="dark" [block]=true>
            Add User
        </CDBBtn>
    </CDBCardBody>
</CDBCard>
<CDBCard
    style="position: relative; width: 25rem; height: 33rem; background-image: url('/assets/img/rectangle.png'); background-repeat: no-repeat; background-position: center">
    <CDBCardBody
        style="background-color: white; width: calc(100% - 50px); text-align: left; align-items: center; position: absolute; bottom: 0px; left: 0px">
        <CDBCardTitle style="color: #333333" class="font-weight-normal">Chukwudi Mezue</CDBCardTitle>
        <CDBCardText style="color: #333333; font-size: 0.9rem" class="font-weight-lighter">Product
            Designer</CDBCardText>
        <CDBCardText style="color: #333333" class="font-weight-light">Enugu, Nigeria</CDBCardText>
        <CDBBtn color="dark" [block]=true class="mt-3">
            Send Message
        </CDBBtn>
    </CDBCardBody>
</CDBCard>
</div>
<div class="example">
<CDBCard
    style="position: relative; width: 25rem; height: 33rem; padding: 25px; background-image: url(/assets/img/rectangle.png); background-repeat: no-repeat; background-position: center;">
    <CDBCardBody
        style="background-color: white; width: calc(100% - 50px); text-align: center; align-items: center; position: absolute; bottom: 25px">
        <CDBCardTitle style="color: #333333" class="font-weight-normal">Mac
            Xenon</CDBCardTitle>
        <CDBCardText style="color: #333333; font-size: 0.9rem" class="font-weight-lighter">Product
            Designer</CDBCardText>
        <CDBCardText style="color: #333333" class="font-weight-light">Enugu,
            Nigeria</CDBCardText>
        <CDBCardBody style="display: flex; justify-content: space-between; padding: 0 50px; margin: 20px 0">
            <CDBIcon size="lg" [fab]=true icon="facebook-f" style="color: #333333"></CDBIcon>
            <CDBIcon size="lg" [fab]=true icon="twitter" style="color: #333333"></CDBIcon>
            <CDBIcon size="lg" [fab]=true icon="instagram" style="color: #333333"></CDBIcon>
        </CDBCardBody>
        <CDBBtn color="dark" [block]=true>
            Add User
        </CDBBtn>
    </CDBCardBody>
</CDBCard>
<CDBCard
    style="position: relative; width: 25rem; height: 33rem; background-image: url('/assets/img/rectangle.png'); background-repeat: no-repeat; background-position: center">
    <CDBCardBody
        style="background-color: white; width: calc(100% - 50px); text-align: left; align-items: center; position: absolute; bottom: 0px; left: 0px">
        <CDBCardTitle style="color: #333333" class="font-weight-normal">Mac
            Xenon</CDBCardTitle>
        <CDBCardText style="color: #333333; font-size: 0.9rem" class="font-weight-lighter">Product
            Designer</CDBCardText>
        <CDBCardText style="color: #333333" class="font-weight-light">Enugu,
            Nigeria</CDBCardText>
        <CDBBtn color="dark" [block]=true class="mt-3">
            Send Message
        </CDBBtn>
    </CDBCardBody>
</CDBCard>
<CDBCard
    style="position: relative; width: 25rem; height: 33rem; background-image: url('/assets/img/rectangle.png'); background-repeat: no-repeat; background-position: center">
    <CDBCardBody
        style="background-color: white; width: 100%; text-align: center; align-items: center; position: absolute; bottom: 0px; left: 0px">
        <CDBCardTitle style="color: #333333" class="font-weight-normal">Mac
            Xenon</CDBCardTitle>
        <CDBCardText style="color: #333333; font-size: 0.9rem" class="font-weight-lighter">Product
            Designer</CDBCardText>
        <CDBCardText style="color: #333333" class="font-weight-light">Enugu,
            Nigeria</CDBCardText>
        <CDBBtn color="dark" [block]=true class="mt-3">
            Send Message
        </CDBBtn>
        <CDBCardBody style="display: flex; justify-content: space-between; padding: 0 50px; margin: 20px 0">
            <CDBBtn [outline]=true [flat]=true color="dark">
                <CDBIcon size="lg" [fab]=true icon="facebook-f" style="color: #333333"></CDBIcon>
            </CDBBtn>
            <CDBBtn [outline]=true [flat]=true color="dark">
                <CDBIcon size="lg" [fab]=true icon="twitter" style="color: #333333"></CDBIcon>
            </CDBBtn>
            <CDBBtn [outline]=true [flat]=true color="dark">
                <CDBIcon size="lg" [fab]=true icon="instagram" style="color: #333333"></CDBIcon>
            </CDBBtn>
        </CDBCardBody>
    </CDBCardBody>
</CDBCard>
</div>
<div class="example">
<CDBCard style="width: 25rem">
    <CDBCardImage class="img-fluid" src="/assets/img/uber.png"></CDBCardImage>
    <div class="mx-auto">
        <CDBPaneImage style="margin-top: -5rem; border-style: solid; border-width: 4px" class="border-white"
            width="130px" src="/assets/img/ellipse.png"></CDBPaneImage>
    </div>
    <CDBCardBody class="d-flex flex-column align-items-center mb-4 pt-1">
        <CDBCardTitle>Chukwudi Mezue</CDBCardTitle>
        <CDBCardText class="text-muted">Product Designer</CDBCardText>
        <CDBCardText style="font-size: 16; color: #333333">Enugu, Nigeria</CDBCardText>
        <CDBCardText style="color: #333333">
            Creating High Quality Resources and tools to Aid developers during the developement of
            their projects
        </CDBCardText>
        <div class="d-flex justify-content-between w-100 mt-3">
            <CDBBtn class="w-100 mr-4" color="dark">Add User</CDBBtn>
            <CDBBtn class="w-100" [outline]=true color="dark"> Send Message </CDBBtn>
        </div>
    </CDBCardBody>
</CDBCard>
<CDBCard style="width: 25rem">
    <CDBCardImage class="img-fluid" src="/assets/img/uber.png"></CDBCardImage>
    <CDBCardBody class="d-flex justify-content-between">
        <CDBPaneImage style="margin-top: -6rem; border-style: solid; border-width: 4px" class="border-white"
            width="130px" src="/assets/img/ellipse.png"></CDBPaneImage>
        <div class="align-items-left pt-1 pb-0">
            <CDBCardTitle>Chukwudi Mezue</CDBCardTitle>
            <CDBCardText class="text-muted">Product Designer</CDBCardText>
        </div>
    </CDBCardBody>
    <CDBCardBody class="d-flex flex-column align-items-center mb-2">
        <CDBCardText style="color: #333333">
            Creating High Quality Resources and tools to Aid developers during the developement of
            their projects
        </CDBCardText>
        <div class="d-flex justify-content-between w-100 mt-3">
            <CDBBtn class="w-100 mr-4" color="dark">Add User</CDBBtn>
            <CDBBtn class="w-100" [outline]=true color="dark"> Send Message </CDBBtn>
        </div>
    </CDBCardBody>
    <CDBCardBody style="display: flex; justify-content: space-between; padding: 0 50px; margin: 0 0 20px">
        <CDBBtn [outline]=true [flat]=true color="dark">
            <CDBIcon size="lg" [fab]=true icon="facebook-f" style="color: #333333"></CDBIcon>
        </CDBBtn>
        <CDBBtn [outline]=true [flat]=true color="dark">
            <CDBIcon size="lg" [fab]=true icon="twitter" style="color: #333333"></CDBIcon>
        </CDBBtn>
        <CDBBtn [outline]=true [flat]=true color="dark">
            <CDBIcon size="lg" [fab]=true icon="instagram" style="color: #333333"></CDBIcon>
        </CDBBtn>
    </CDBCardBody>
</CDBCard>
<CDBCard style="width: 25rem">
    <div class="mx-auto">
        <CDBPaneImage style="margin-top: 2rem; border-style: solid; border-width: 4px" class="border-white"
            width="130px" src="/assets/img/ellipse.png"></CDBPaneImage>
    </div>
    <CDBCardBody class="d-flex flex-column align-items-center mb-4 pt-1">
        <CDBCardTitle>Chukwudi Mezue</CDBCardTitle>
        <CDBCardText class="text-muted">Product Designer</CDBCardText>
        <CDBCardText style="font-size: 16px; color: #333333">Enugu, Nigeria</CDBCardText>
        <CDBCardText class="mt-3" style="color: #333333">
            Creating High Quality Resources and tools to Aid developers during the developement of
            their projects
        </CDBCardText>
        <div class="w-100 mt-3">
            <CDBBtn class="w-100 mb-3" color="dark">Send Message</CDBBtn>
            <CDBBtn class="w-100" [outline]=true color="dark"> Send Message </CDBBtn>
        </div>
    </CDBCardBody>
</CDBCard>
</div>
<div class="example">
<CDBCard style="width: 25rem">
    <CDBCardImage class="img-fluid" src="/assets/img/uber.png"></CDBCardImage>
    <div class="mx-auto">
        <CDBPaneImage style="margin-top: -5rem; border-style: solid; border-width: 4px" class="border-white"
            width="130px" src="/assets/img/ellipse.png"></CDBPaneImage>
    </div>
    <CDBCardBody class="d-flex flex-column align-items-center mb-4 pt-1">
        <CDBCardTitle>Chukwudi Mezue</CDBCardTitle>
        <CDBCardText class="text-muted">Product Designer</CDBCardText>
        <CDBCardText style="font-size: 16px; color: #333333">Enugu, Nigeria</CDBCardText>
        <div class="w-100 mt-3">
            <CDBCardBody
                style="display: flex; justify-content: space-between; padding: 0 70px; margin: 10px 0 30px">
                <div class="mx-auto">
                    <CDBIcon size="lg" [fab]=true icon="facebook-f" style="color: #333333"></CDBIcon>
                </div>
                <div class="mx-auto">
                    <CDBIcon size="lg" [fab]=true icon="twitter" style="color: #333333"></CDBIcon>
                </div>
                <div class="mx-auto">
                    <CDBIcon size="lg" [fab]=true icon="instagram" style="color: #333333"></CDBIcon>
                </div>
            </CDBCardBody>
        </div>
        <div class="w-100">
            <CDBBtn class="w-100 mb-3" color="dark">Add User</CDBBtn>
            <CDBBtn class="w-100" [outline]=true color="dark"> Send Message </CDBBtn>
        </div>
    </CDBCardBody>
</CDBCard>
<CDBCard style="width: 25rem">
    <CDBCardImage class="img-fluid" src="/assets/img/uber.png"></CDBCardImage>
    <div class="mx-auto">
        <CDBPaneImage style="margin-top: -5rem; border-style: solid; border-width: 4px" class="border-white"
            width="130px" src="/assets/img/ellipse.png"></CDBPaneImage>
    </div>
    <CDBCardBody class="d-flex flex-column align-items-center mb-4 pt-1">
        <CDBCardTitle>Chukwudi Mezue</CDBCardTitle>
        <CDBCardText class="text-muted">Product Designer</CDBCardText>
        <CDBCardText style="font-size: 16; color: #333333">Enugu, Nigeria</CDBCardText>
        <CDBCardText style="color: #333333; margin: 20px 0 30px">
            Creating High Quality Resources and tools to Aid developers during the developement of
            their projects
        </CDBCardText>
        <div class="w-100">
            <CDBBtn class="w-100 mb-0" color="dark">Send Message</CDBBtn>
        </div>
    </CDBCardBody>
</CDBCard>
<CDBCard style="width: 25rem">
    <div class="mx-auto">
        <CDBPaneImage style="margin-top: -5rem; border-style: solid; border-width: 4px" class="border-white"
            width="130px" src="/assets/img/ellipse.png"></CDBPaneImage>
    </div>
    <CDBCardBody class="d-flex flex-column align-items-center mb-4 pt-1">
        <CDBCardTitle>Chukwudi Mezue</CDBCardTitle>
        <CDBCardText class="text-muted">Product Designer</CDBCardText>
        <CDBCardText style="font-size: 16; color: #333333">Enugu, Nigeria</CDBCardText>
        <CDBCardText class="mt-3" style="color: #333333">
            Creating High Quality Resources and tools to Aid developers during the developement of
            their projects
        </CDBCardText>
        <div class="w-100 mt-3">
            <CDBBtn class="w-100 mb-3" color="dark">Send Message</CDBBtn>
            <CDBBtn class="w-100" [outline]=true color="dark"> Send Message </CDBBtn>
        </div>
    </CDBCardBody>
</CDBCard>
```

# API

This section will build on your information about the props you get to use with the Contrast Angular Bootstrap Card component. You will find out what these props do, their default values, and how you would use them in your code.


## API Reference: Contrast Card Inputs

The table below lists other prop options of the `CDBCard` component.

| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
| class      | String       |              |Adds custom classes	      |     class="myClass" |
| color          | String       |              | Sets background color | color="dark" |
| border         | Boolean      | false        | Gives border | border=true |



## API Reference: Contrast Card Body Properties

The table below lists other prop options of the `CDBCardBody` component.

| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
| class      | String       |              |Adds custom classes	      |   class="myClass" |
| cascade        | Boolean      | false        | Switches the card's body to cascade style mode | cascade=true |


## API Reference: Contrast Card Image Properties

The table below lists other prop options of the `CDBCardImage` component.

| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
| class      | String       | |Adds custom classes	      |     class="myClass" |
| cascade        | Boolean      | false        | Switches the card's body to cascade style mode | cascade=true |
| hover          | Boolean      | false        | Switches on hover behavior | hover=true  |
| overlay        | String       | white-light  | Sets the color of hover overlay | overlay="white-light" |
| src            | String       |              | Source of the image | src="image_src" |
| top            | Boolean      | false        | Makes image fluid | top=true |


## API Reference: Contrast Card Text Properties

The table below lists other prop options of the `CDBCardText` component.

| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
| class      | String       |              |Adds custom classes	      |     class="myClass" |
| muted          | Boolean      | false        | Mutes the text color | muted=true |
| small          | Boolean      | false        | Uses html `small` as component's tag | small=true |


## API Reference: Contrast Card Title Properties

The table below lists other prop options of the `CDBCardTitle` component.

| Name            | Type        | Default      |   Description| Example      |
| :------------- | :----------: | -----------: | :----------: | -----------: |
| class      | String       |              |Adds custom classes	      |     class="myClass" |
| sub            | Boolean      | false        | Styles title as subtitle | sub=true |
