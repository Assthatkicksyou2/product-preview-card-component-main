# product-preview-card-component-main

Product preview card flexbox image and content

To make an image and content within one flexbox, be careful to use the right amount of <div>
First,

- {
  box-sizing: border-box;
  }

<img div> SHOULD have border-radius, with it, <img> will not need it
.image-container {
display: flex;
flex-direction: column;
width: 50%;
border-radius: 10px 0 0 10px;
overflow: hidden;
}
.image-container img {
width: 100%;
height: 100%;
}
