<script setup>
import Personal from '@/components/Personal.vue'

</script>


<template>
    <div class="container">
        <div class="box1">
            <div class="gambar">
                <img alt="Logo" src="@/assets/diancv(2).png" />
            </div>
            <div class="konten">
                <div class="konten1">
                    <h1>Aldriani Saputra.</h1>
                    <h2>Front End Developer</h2>
                    <hr>
                    <div class="box2">
                        <div class="about">
                            <p>0858-8217-4829</p>
                        </div>
                        <!-- <div class="garis1"></div> -->
                        <div class="about">
                            <p>aldrianisaputra04@gmail.com</p>
                        </div>
                        <!-- <div class="garis1"></div> -->
                        <div class="about">
                            <p>Depok, West Java</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- <hr> -->
        <div class="box3">
            <div class="personal">
                <h3>ABOUT ME</h3>
                <p>My name is Aldriani Saputra, I am a student from Taruna Bhakti Vocational High School who is
                    interested in information technology (IT) fields such as design and programming.</p>
            </div>
            <div class="personal">
                <h3>EDUCATION</h3>
                <ul>
                    <li>2020 - Now. <br> Taruna Bhakti Vocational high school.<br> Software Engineering / RPL.</li>
                </ul>
            </div>
            <div class="personal">
                <h3>EXPERIENCE</h3>
                <ul>
                    <li>2021 <br> Aplikasi Inventory Sarana dan Prasarana </li>
                    <li>2022 <br> Aplikasi Agenda</li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style scoped>
.container {
    background: #AE7978;
    color: white;
    /* padding: 30px 30px; */
    border-radius: 10px;
    box-shadow: 0 20px #AE7978;
    height: 800px;
    width: 100%;
}

.container h1 {
    font-size: 50px;
    font-weight: 600;
    /* text-align: center; */
}

.box1 {
    display: flex;
    justify-content: space-evenly;
    width: 100%;
    padding-top: 170px;
    padding-left: 40px;

}

.box1 .gambar {
    width: 350px;
    margin: -90px 40px 0 40px;
}

.box1 .konten {
    width: 750px;
    margin: -120px 0 0 0;
}

.konten1 {
    padding-right: 90px;
}

.konten1 h1 {
    font-size: 40px;
    padding-top: 90px;
}

.konten1 h2 {
    font-weight: lighter;
    font-size: 20px;
}

.gambar img {
    width: 300px;
    height: 300px;
    border-radius: 100%;
    margin: -20px 20px 0 0;

}

.box2 {
    display: flex;
    justify-content: space-evenly;
    width: 100%;
    /* height: 500px; */
    margin-top: 20px;
    padding-top: 30px;
    /* background: transparent; */
    /* border-style: solid;
    border-color: white;
    border-radius: 30px; */

}

.about {
    width: 200px;
    margin: -30px 30px 0 30px;
}

.about p {
    text-align: center;
}

.garis1 {
    width: 4px;
    height: 20px;
    background-color: aliceblue;
    margin-top: -30px;
}

.box3 {
    display: flex;
    justify-content: space-evenly   ;
    width: 100%;
    /* height: 500px; */
    margin-top: 60px;
    /* background: transparent; */
    /* border-style: solid;
    border-color: white;
    border-radius: 30px; */
}

.personal {
    width: 300px;
    height: 300px;
    border-style: groove;
    border-width: 2px;
    border-color: white;
    border-radius: 10px;
    padding: 40px;
}

.personal h3 {
    font-weight: 600;
    text-align: center;
    padding-bottom: 10px;
}
.hr{
    margin-top: 60px;
}
</style>