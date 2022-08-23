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
                            <p><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-phone"><path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"></path></svg>
                            <br> 0858-8217-4829</p>
                        </div>
                        <!-- <div class="garis1"></div> -->
                        <div class="about">
                            <p><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-mail"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"></path><polyline points="22,6 12,13 2,6"></polyline></svg>aldrianisaputra04@gmail.com</p>
                        </div>
                        <!-- <div class="garis1"></div> -->
                        <div class="about">
                            <p><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-map-pin"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"></path><circle cx="12" cy="10" r="3"></circle></svg> <br> Depok, West Java</p>
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