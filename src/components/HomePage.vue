<template>
<div class="body">
<div class="navbar">
<div class="navbar-el">Tpunk</div>
<div class="navbar-el">Search</div>
<div class="navbar-el">Market</div>
<div class="navbar-el">Create</div>

<div class="navbar-el">My Tpunks</div>
<div class="navbar-el">25 TPK</div>
</div>
<div class="entre"></div>
<div class="row-box">
<div class="box box1">CONCERT</div>
<div class="box box2">FESTIVAL</div>
<div class="box box3">EXPOSITION</div>
</div>
<div>hello</div>
</div>
</template>

<script>
export default {
  name: 'HomePage',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.body{
  height: 800px;
  background-color: whitesmoke;
}
.entre{
  height: 1px;
  background-color: black;
}
.row-box{
  display: flex;
  justify-content: space-around;
  align-items: center;
  height: 250px;
  background-color: whitesmoke;
}
.box{
  height: 90%;
  width: 25%;
  border-radius: 20px;
}

.box1{
  background-image: url(https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS5W7oACseaIGYdQ7OG51LNO3z09dNhCIU52A&usqp=CAU);
background-repeat: no-repeat;
  background-position: center;
  height: 73%;
  width: 18%;
  color: white;
  font-size: 2rem;
}

.box2{
  background-image: url(https://tonedeaf.thebrag.com/wp-content/uploads/2019/08/ultra-768x435.jpg);
background-repeat: no-repeat;
  background-position: center;
  height: 73%;
  width: 18%;
    color: white;
  font-size: 2rem;
}

.box3{
  background-image: url(https://images.theconversation.com/files/209362/original/file-20180307-146661-1br3u6a.jpg?ixlib=rb-1.1.0&rect=62%2C46%2C1314%2C915&q=45&auto=format&w=496&fit=clip);
background-repeat: no-repeat;
  background-position: bottom;
  height: 73%;
  width: 18%;
    color: white;
  font-size: 2rem;
}
.navbar{
  display: flex;
  justify-content: space-around;
  align-items: center;
  background-color:rgb(50, 57, 57);
  padding: 1rem;
  width: 100%;
}
.navbar-el{
  border: solid 1px;
  border-radius: 25%;
  padding: 1rem;
  width: 50px;
  font-weight: bold;
  color: rgb(50, 57, 57);
  background-color:whitesmoke;
}
</style>
