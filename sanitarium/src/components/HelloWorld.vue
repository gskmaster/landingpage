<template>
  <div class="min-h-screen flex flex-col">
    <header class="bg-gray-100 py-4 w-full fixed top-0">
      <nav class="container mx-auto p-4 flex justify-between md:flex">
        <div class="flex items-center">
          <img src="#" alt="Logo" class="h-8 w-8 mr-2">
          <span class="text-lg font-bold">Logo</span>
        </div>
        <button class="md:hidden" aria-label="Toggle navigation">
          <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16" />
          </svg>
        </button>
        <ul class="hidden md:flex flex-wrap justify-end">
          <li class="mr-6"><a href="#about" class="text-gray-600 hover:text-gray-900">About</a></li>
          <li class="mr-6"><a href="#features" class="text-gray-600 hover:text-gray-900">Features</a></li>
          <li><a href="#contact" class="text-gray-600 hover:text-gray-900">Contact</a></li>
        </ul>
      </nav>
    </header>
    <main class="flex-1">
      <section id="about" class="hero is-fullheight h-screen bg-cover bg-center"
        style="background-image: url('https://picsum.photos/2000/1000'); height: 1000px;">
        <div class="container mx-auto p-4 pt-6 md:p-6 lg:p-12 flex justify-center items-center h-screen">
          <div class="text-center">
            <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold text-white">About Us</h1>
            <p class="text-lg md:text-xl lg:text-2xl text-white mb-4">Lorem ipsum dolor sit amet, consectetur adipiscing
              elit. Sed sit amet nulla auctor, vestibulum magna sed, convallis ex.</p>
            <button class="bg-orange-500 hover:bg-orange-700 text-white font-bold py-2 px-4 rounded">Learn More</button>
          </div>
        </div>
      </section>
      <section id="features" class="py-20">
        <div class="mx-auto px-4 py-16">
          <h2 class="text-3xl font-bold text-gray-800 text-center mb-12">What We Do?</h2>
          <h3 class="text-2xl font-bold text-gray-800 text-center mb-4">Perfect Solution For Your Business</h3>
          <p class="text-gray-600 text-center mb-16">Launch your campaign and benefit from our expertise on designing
            and managing conversion centered Tailwind CSS html page.</p>

          <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
            <div class="bg-white rounded-lg shadow-md p-6">
              <div class="flex items-center justify-center mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" class="w-12 h-12 text-orange-500" fill="none"
                  viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                    d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
              </div>
              <h4 class="text-xl font-bold text-gray-800 mb-2">Grow Your Business</h4>
              <p class="text-gray-600 mb-4">The phrasal sequence of the is now so that many campaign and benefit.</p>
              <a href="#"
                class="inline-block bg-orange-500 hover:bg-orange-600 text-white font-bold py-2 px-4 rounded-full">Read
                More →</a>
            </div>
            <div class="bg-white rounded-lg shadow-md p-6">
              <div class="flex items-center justify-center mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" class="w-12 h-12 text-orange-500" fill="none"
                  viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4v16m8-8H4" />
                </svg>
              </div>
              <h4 class="text-xl font-bold text-gray-800 mb-2">Drive More Sales</h4>
              <p class="text-gray-600 mb-4">The phrasal sequence of the is now so that many campaign and benefit.</p>
              <a href="#"
                class="inline-block bg-orange-500 hover:bg-orange-600 text-white font-bold py-2 px-4 rounded-full">Read
                More →</a>
            </div>
            <div class="bg-white rounded-lg shadow-md p-6">
              <div class="flex items-center justify-center mb-4">
                <svg xmlns="http://www.w3.org/2000/svg" class="w-12 h-12 text-orange-500" fill="none"
                  viewBox="0 0 24 24" stroke="currentColor">
                  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                    d="M12 8v4m0 4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
                </svg>
              </div>
              <h4 class="text-xl font-bold text-gray-800 mb-2">Handled By Expert</h4>
              <p class="text-gray-600 mb-4">The phrasal sequence of the is now so that many campaign and benefit.</p>
              <a href="#"
                class="inline-block bg-orange-500 hover:bg-orange-600 text-white font-bold py-2 px-4 rounded-full">Read
                More →</a>
            </div>
          </div>
        </div>
      </section>
      <section id="contact" class="py-20">
        <div class="mx-auto px-4 py-16">
          <div class="text-center mb-8">
            <h1 class="text-3xl font-bold text-gray-800">Get In Touch!</h1>
            <p class="text-gray-600">Launch your campaign and benefit from our expertise on designing and managing
              conversion centered Tailwind CSS html page.</p>
          </div>
          <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
            <div class="bg-white rounded-lg shadow-md p-8">
              <form>
                <div class="mb-4">
                  <label for="name" class="block text-gray-700 font-bold mb-2">Name:</label>
                  <input type="text" id="name"
                    class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" />
                </div>
                <div class="mb-4">
                  <label for="email" class="block text-gray-700 font-bold mb-2">Email:</label>
                  <input type="email" id="email"
                    class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" />
                </div>
                <div class="mb-4">
                  <label for="subject" class="block text-gray-700 font-bold mb-2">Subject:</label>
                  <input type="text" id="subject"
                    class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline" />
                </div>
                <div class="mb-6">
                  <label for="message" class="block text-gray-700 font-bold mb-2">Message:</label>
                  <textarea id="message"
                    class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline"></textarea>
                </div>
                <div class="flex items-center justify-center">
                  <button type="submit"
                    class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded focus:outline-none focus:shadow-outline">Send
                    Message</button>
                </div>
              </form>
            </div>
            <div class="bg-white rounded-lg shadow-md p-8">
              <div class="mb-4">
                <h2 class="text-lg font-bold text-gray-800">Contact Information</h2>
              </div>
              <div class="mb-4">
                <i class="fas fa-phone-alt text-gray-800 mr-2"></i>
                <a href="tel:+152534468854" class="text-gray-800">+152 534-468-854</a>
              </div>
              <div class="mb-4">
                <i class="fas fa-envelope text-gray-800 mr-2"></i>
                <a href="mailto:contact@example.com" class="text-gray-800">contact@example.com</a>
              </div>
              <div class="mb-4">
                <i class="fas fa-map-marker-alt text-gray-800 mr-2"></i>
                <address class="text-gray-800">C/54 Northwest Freeway, Suite 558,<br> Houston, USA 485</address>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>
    <footer class="bg-gray-100 py-4">
      <p class="text-center text-gray-600">&copy; 2023 Our App</p>
    </footer>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: '',
      email: ''
    }
  }
}
</script>