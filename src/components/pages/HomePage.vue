<template>
    <div class="wrapper">
        <div class="content">
            <div class="top-block">
                <input type="search" name="search" class="input-home" placeholder="Find the desired book...">
            </div>
            <div class="bottom-block">
                <div class="grid-container">
                    <div class="grid-top">
                        <img src="src/assets/images/book.jpg" alt="">
                    </div>
                    <div class="grid-bottom">
                        <h3>Book Name</h3>
                        <div class="grid-bottom-footer">
                            <p>book writer</p>
                            <button class="btn btn-grid">Details</button>
                        </div>
                    </div>
                </div>
                <div class="grid-container">
                    <div class="grid-top">
                        <img src="" alt="">
                    </div>
                    <div class="grid-bottom">
                        <h3>Book Name</h3>
                        <div class="grid-bottom-footer">
                            <p>book writer</p>
                            <button class="btn btn-grid">Details</button>
                        </div>
                    </div>
                </div>
                <div class="grid-container">
                    <div class="grid-top">
                        <img src="" alt="">
                    </div>
                    <div class="grid-bottom">
                        <h3>Book Name</h3>
                        <div class="grid-bottom-footer">
                            <p>book writer</p>
                            <button class="btn btn-grid">Details</button>
                        </div>
                    </div>
                </div>
                <div class="grid-container">
                    <div class="grid-top">
                        <img src="" alt="">
                    </div>
                    <div class="grid-bottom">
                        <h3>Book Name</h3>
                        <div class="grid-bottom-footer">
                            <p>book writer</p>
                            <button class="btn btn-grid">Details</button>
                        </div>
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
.content {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
}

.top-block {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 2rem;
    width: 60%;
}

.input-home {
    width: 40%;
    height: 2.5rem;
}

.bottom-block {
    width: 100%;
    display: grid;
    grid-template-columns: auto auto auto auto;
    gap: 1rem;
    margin-top: 5rem;
    justify-content: space-evenly;
}

.grid-container {
    background-color: #293241;
    padding: 1rem;
    width: 400px;
    height: 300px;
    border-radius: 8px;
    box-shadow: 0px 0px 33px 2px rgba(61, 90, 128, 1);
}

.grid-container:hover {
    transform: scale(1.03);
}

.grid-top {
    height: 50%;
    width: 100%;
}

.grid-bottom {
    width: 100%;
    height: 50%;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

.grid-bottom h3 {
    margin-top: 2rem;
}

.grid-bottom-footer {
    display: flex;
    justify-content: space-between;
    margin-left: 0.7rem;
    margin-right: 0.7rem;
}
</style>