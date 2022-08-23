<template>
    <div class="container">
        <h1>MY SKILL</h1>
        <div class="garis"></div>
        <div class="box1">
            <div class="konten1">
                <div class="isi">
                    <p>HTML & CSS</p>
                </div>
            </div>
            <div class="progress">
                <div class="progress-bar progress-bar-striped bg-black" role="progressbar" style="width: 80%;" aria-valuenow="25"
                aria-valuemin="0" aria-valuemax="100">80%</div>
            </div>
        </div>
        <div class="box1">
            <div class="konten1">
                <div class="isi">
                    <p>PHP & MySQL</p>
                </div>
            </div>
             <div class="progress">
                <div class="progress-bar progress-bar-striped bg-black" role="progressbar" style="width: 60%;" aria-valuenow="25"
                aria-valuemin="0" aria-valuemax="100">60%</div>
            </div>
        </div>
        <div class="box1">
            <div class="konten1">
                <div class="isi">
                    <p>JavaScripts</p>
                </div>
            </div>
             <div class="progress">
                <div class="progress-bar progress-bar-striped bg-black" role="progressbar" style="width: 50%;" aria-valuenow="25"
                aria-valuemin="0" aria-valuemax="100">50%</div>
            </div>
        </div>
        <div class="box1">
            <div class="konten1">
                <div class="isi">
                    <p>Laravel</p>
                </div>
            </div>
             <div class="progress">
                <div class="progress-bar progress-bar-striped bg-black" role="progressbar" style="width: 40%;" aria-valuenow="25"
                aria-valuemin="0" aria-valuemax="100">40%</div>
            </div>
        </div>
         <div class="box1">
            <div class="konten1">
                <div class="isi">
                    <p>Figma Design</p>
                </div>
            </div>
             <div class="progress">
                <div class="progress-bar progress-bar-striped bg-black" role="progressbar" style="width: 80%;" aria-valuenow="25"
                aria-valuemin="0" aria-valuemax="100">80%</div>
            </div>
        </div>
         <div class="box1">
            <div class="konten1">
                <div class="isi">
                    <p>Bootstrap</p>
                </div>
            </div>
             <div class="progress">
                <div class="progress-bar progress-bar-striped bg-black" role="progressbar" style="width: 80%;" aria-valuenow="25"
                aria-valuemin="0" aria-valuemax="100">80%</div>
            </div>
        </div>
    </div>
</template>


<style scoped>
.container {
    height: 400px;
    background: #AE7978;
    color: white;
    text-align: center;
    /* padding: 30px 30px; */
    border-radius: 10px;
    height: 700px;
    margin-bottom: -20px;

}

h1 {
    padding: 10px;
    font-weight: bold;
}

.garis {
    width: 100%;
    height: 5px;
    background-color: white;

}

.box1 {
    display: flex;
    justify-content: space-evenly;
    width: 100%;
    padding: 50px 40px 0px 40px;
}

.konten1 {
    width: 300px;
}

.progress {
    width: 700px;
}
</style>