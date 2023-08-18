The REGISTER-FORM.HTML file is a HTML form that collects user information. The form has two sections, one for the user's contact information and one for their company information. The user can enter their name, email address, phone number, job title, company, address, and website. They can also enter a description of their company, the products or services they want to exhibit, and their preferred booth type. Finally, they can list their staff and competitors. The form has two buttons, one to submit the form and one to reset it.

Here are the steps on how to create a form in HTML:

1. Start by creating a new HTML file.
2. Add the following code to the head of the file:

```
<meta charset="UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=edge">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>FORM</title>
<style>
* {
    margin: 0px;
    padding: 0px;
}

.fullContent {
    display: flex;
    background-color: beige;
    padding-bottom: 5%;



}

.leftContent {
    display: flex;
    flex: 40%;
    flex-direction: column;
    justify-content: center;
    padding: 5px;
    margin-left: 10%;
    width: 500px;

}

.rightContent {
    display: flex;
    flex: 40%;
    flex-direction: column;
    margin-right: 10%;
    padding-left: 100px;
    padding: 5px;

}

.inputBox {
    width: 35%;
    height: 50px;
    position: relative;
    /* NOTE = IF we need to give text box any other kind of input in front of lable data like in this form so we give that lable anf input tag in the seprate div and then set the style as we need  */
    display: inline-block;
    text-align: center;
}

.input