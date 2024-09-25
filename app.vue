<template>
  <div class="min-h-screen flex flex-col">
    <!-- Navbar -->
    <nav class="bg-blue-900 text-white p-4">
      <div class="container mx-auto flex justify-between items-center">
        <h1 class="text-2xl font-bold">Ramadhani Maulana Raharjo</h1>
        <div>
          <a href="#about" class="px-4">About</a>
          <a href="#projects" class="px-4">Projects</a>
          <a href="https://wa.me/qr/XWTGFXG43NFZP1" class="px-4">Contact</a>
        </div>
      </div>
    </nav>

    <!-- Main Content -->
    <main class="flex-grow container mx-auto p-8">
      <!-- Hero Section -->
      <section class="text-center py-12" id="about">
        <h2 class="text-4xl font-bold mb-4">Hai, Saya Ramadhani Maulana Raharjo</h2>
        <p class="text-lg text-gray-700">Selamat datang di CV saya. Hobi saya fotografer, jalan-jalan, dan saya sangat
          suka dengan kucing. Saya saat ini sedang
          berkuliah di Universitas Brawijaya dan sedang berproses meraih masa depan yang cerah.</p>
        <img src="./assets/PAS FOTO UB.jpg" alt="Profile Picture" class="rounded-full mx-auto my-8" width="200">
        <div class="card education-card p-80 w-80 mx-auto">
          <div class="card-header"><i class="fas fa-graduation-cap"></i>
            <h2 class="font-bold">Riwayat Pendidikan</h2>
          </div>
          <ul>
            <li>SMP KARTIKA IV-9 MALANG (2017-2020)</li>
            <li>---</li>
            <li>SMK NEGERI 8 MALANG (2020-2023)</li>
          </ul>
        </div>
      </section>

      <!-- Links Section -->
      <section class="py-12" id="projects">
        <h3 class="text-3xl font-semibold text-center mb-8">SOCIAL MEDIA, YOUTUBE CHANEL & GITHUB</h3>
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
          <!-- Instagram Link -->
          <a href="https://www.instagram.com/rmdhanimr_?igsh=ODk5MGRxOWc3d3Rr" target="_blank"
            class="bg-white shadow-lg rounded-lg overflow-hidden">
            <img src="./assets/ig.jpg" alt="Instagram" class="w-full">
            <div class="p-4">
              <h4 class="text-xl font-bold">Instagram</h4>
              <p class="text-gray-600">Mutualan Kuyy</p>
            </div>
          </a>

          <!-- YouTube Link -->
          <a href="https://youtube.com/@dhaniii?si=fCgh_P1z60Z9AEeq" target="_blank"
            class="bg-white shadow-lg rounded-lg overflow-hidden">
            <img src="./assets/yutub.jpg" alt="YouTube" class="w-full">
            <div class="p-4">
              <h4 class="text-xl font-bold">YouTube</h4>
              <p class="text-gray-600">Subscribe to my YouTube channel</p>
            </div>
          </a>

          <!-- LinkedIn Link -->
          <a href="https://github.com/Ramadhani-Maulana" target="_blank"
            class="bg-white shadow-lg rounded-lg overflow-hidden">
            <img src="./assets/image.png" alt="LinkedIn" class="w-full">
            <div class="p-4">
              <h4 class="text-xl font-bold">My Github</h4>
              <p class="text-gray-600">Check my project</p>
            </div>
          </a>
        </div>
      </section>
    </main>

    <!-- Footer -->
    <footer class="bg-blue-900 text-white p-4 text-center">
      <p>&copy; 2024 Ramadhani Maulana Raharjo.</p>
    </footer>
  </div>
</template>

<script>
export default {
  head() {
    return {
      title: 'Ramadhani Maulana Raharjo Portfolio',
    }
  }
}
</script>

<style>
/* Tailwind CSS is handling most of the styling */
.card {
    background-color: #fff;
    border-radius: 12px;
    box-shadow: 0 6px 12px #00000026;
    flex: 1;
    padding: 25px;
    text-align: left;
    transition: transform .3s ease
}
.card:hover {
    transform: translateY(-10px)
}

.card-header {
    align-items: center;
    display: flex;
    margin-bottom: 20px
}

.card-header i {
    color: #4a90e2;
    font-size: 1.5em;
    margin-right: 10px
}

.card h2 {
    color: #333;
    font-size: 1.7em;
    margin: 0
}
</style>
