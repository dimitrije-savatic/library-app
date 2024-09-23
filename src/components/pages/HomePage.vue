<template>
    <div class="wrapper">
        <div class="content">
            <div class="top-block">
                <input type="search" name="search" class="input-home" placeholder="Find the desired book...">
            </div>
            <div class="bottom-block">
                <div class="grid-container" v-for="(book, index) in books" :key="index">
                    <div class="grid-top">
                        <img src="../../assets/images/book.jpg" alt="book">
                    </div>
                    <div class="grid-bottom">
                        <h3>{{ book.name }}</h3>
                        <div class="grid-bottom-footer">
                            <p>{{ book.author }}</p>
                            <button class="btn btn-grid">Details...</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    components: {
    },
    data() {
        return {
            books: [{
                'name': 'Lord of the Rings',
                'author': 'J.R.R. Tolkien'
            },
            {
                'name': 'Lord of the Rings',
                'author': 'J.R.R. Tolkien'
            },
            {
                'name': 'Lord of the Rings',
                'author': 'J.R.R. Tolkien'
            },
            {
                'name': 'Lord of the Rings',
                'author': 'J.R.R. Tolkien'
            },
            {
                'name': 'Lord of the Rings',
                'author': 'J.R.R. Tolkien'
            },
            {
                'name': 'Lord of the Rings',
                'author': 'J.R.R. Tolkien'
            },
            {
                'name': 'Lord of the Rings',
                'author': 'J.R.R. Tolkien'
            },
            {
                'name': 'Lord of the Rings',
                'author': 'J.R.R. Tolkien'
            },
            ]
        }
    }
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
    gap: 2rem 1rem;
    margin-top: 5rem;
    margin-bottom: 5rem;
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
    height: 60%;
    width: 100%;
}

.grid-top img {
    background-position: center;
    background-attachment: inherit;
    background-repeat: no-repeat;
    width: 100%;
    height: 100%;
    border-radius: 8px;
}

.grid-bottom {
    width: 100%;
    height: 40%;
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
    align-items: baseline;
    margin-left: 0.7rem;
    margin-right: 0.7rem;
}
</style>