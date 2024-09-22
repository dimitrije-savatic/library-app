<template>
  <div class="wrapper">
    <div class="content">
        <div class="top-block">
            <div class="search-bar">
                <input type="search" name="search">
            </div>
        </div>
        <div class="bottom-block">
            <div class="grid">
                <div class="grid-top">
                    <img src="" alt="">
                </div>
                <div class="grid-bottom">
                    <h3>Book Name</h3>
                    <p>book writer</p>
                    <button class="btn">Rent</button>                    
                </div>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.content{
    display: flex;
    flex-direction: column;
    width: 100%;
}
.top-block{
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 2rem;
    width: 60%;
}
</style>