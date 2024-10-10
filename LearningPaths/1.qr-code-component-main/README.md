# Frontend Mentor - QR code component solution

First solution created for the QR Code component challenge provided by FrontEnd Mentor through the Learning Paths program.  
- The challenge consists of creating a static page with a content container providing the QR Code image and a description below it. The design is shown below.

![design page QR COde componente](./preview.jpg)

### Links
The project solution is hosted on Vercel at the following link below:

Vercel: [https://qrcode-page.vercel.app/](https://qrcode-page.vercel.app/)

### Tecnologias utilizadas

- HTML and CSS static.

### What I learned

This was my first practical project involving creating pages from scratch, as a challenge for myself. I was able to put into practice some of the knowledge I’ve acquired about FrontEnd so far, covering almost all aspects of the solution creation.   
I managed to apply some positioning fundamentals and practice better solutions involving images, focusing on the use of `background-image` in CSS.  
The solution does not use FlexBox or Grid for positioning manipulation by choice, as I wanted to practice object centering in other ways.

My main challenge was creating the main container and its styling and centering, so the elements inside it would be positioned correctly.

```CSS:
.centerConteiner{
    background-color: hsl(0, 0%, 100%);
    border-radius: 10px; /* certo. */
    box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
    max-width: 250px;

    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);

    padding: 15px;
}
```

### Autor:
Benjamin Marcos  
Github: [https://github.com/Beenjmin](https://github.com/Beenjmin)

---