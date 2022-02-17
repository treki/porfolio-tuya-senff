<template>
   <h3 id="text-center"> </h3>
<div class="container-contact">
     
    <div class="form" id="text-center">
    <form>
       <h3>Have a question or want to work together?</h3>
        <input type="text" id="name" placeholder="Name" required>
        <input type="email" id="email" placeholder="Enter email" required>
        <textarea id="message" rows="4" placeholder="Your message" required></textarea>
        <button type="submit">Submit</button>
    </form>
    </div>
</div>
</template>

<style scoped>
.container-contact{
    width: 100%;
    height: 50vh;
    display: flex;
    align-items: center;
    justify-content: center;
}
form{
    background: #686363;
    display: flex;
    flex-direction: column;
    padding: 2vw 4vw;
    width: 90%;
    max-width: 600px;
    border-radius: 5px;
    margin-bottom: 40px;
}
form h5{
    color: #ffffff;
}
form input, form textarea{
    border: 0;
    margin: 10px 0;
    padding: 20px;
    outline: none;
    background: #fafafa;

    font-size: 20px;
    border-radius: 5px;;
}
form button{
    margin: 20px;
    cursor: pointer;
    background-color: transparent;      
    color: #fcfcfc;
    font-size: 25px;
    border-color: #d1cfcf;     
}
form button:hover{
      background: rgb(90, 90, 90);
    color: #ffffff;
}
</style>