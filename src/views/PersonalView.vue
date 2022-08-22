<script setup>
import Personal from '@/components/Personal.vue'
</script>

<template>
    <div class="container">
        <h1>Personal</h1>
        <div class="garis"></div>
        <div class="box1">
            <div class="gambar">
                <img alt="Logo" src="@/assets/markk.jpg" />
            </div>
            <div class="konten">
                <div class="konten1">
                    <h2>About Me</h2>
                    <p>My name is Aldriani Saputra, I am a student from Taruna Bhakti Vocational High School who is
                        interested in information technology (IT) fields such as design and programming.</p>
                    <hr>
                    <h2>About Me</h2>
                    <p>My name is Aldriani Saputra, I am a student from Taruna Bhakti Vocational High School who is
                        interested in information technology (IT) fields such as design and programming.</p>
                    <hr>
                    <h2>About Me</h2>
                    <p>My name is Aldriani Saputra, I am a student from Taruna Bhakti Vocational High School who is
                        interested in information technology (IT) fields such as design and programming.</p>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.container {
    background: #AE7978;
    color: white;
    /* padding: 30px 30px; */
    border-radius: 30px;
    box-shadow: 0 20px #AE7978;
    height: 500px;
}

.container h1 {
    font-size: 50px;
    font-weight: 600;
    text-align: center;
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
    height: 500px;
    padding: 150px 40px;

}

.box1 .gambar {
    width: 300px;
    margin: -90px 40px 0 40px;
}

.box1 .konten {
    width: 700px;
    margin: -120px 0 0 0;
}

.konten1 {
    padding-right: 90px;
}

.konten1 h2 {
    font-weight: 600;
}

.gambar img {
    width: 300px;
    height: 300px;
    border-radius: 30px;
    margin: -20px 20px 0 0;

}
</style>