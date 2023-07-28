---
title: Contact Page
menu:
    main: 
        weight: -50
        params:
            icon: contact

comments: false
---

Do you have to contact me? No problem, you can understand where you contact me in ***this page***.

<a href="https://gthz.it/em"><img src="mail.png" width="48px" height="48px"></a>

<p> <a href="mailto:me@gianstech.it">me@gianstech.it</a> (Personal Email) - <a href="mailto:info@gianstech.it">info@gianstech.it</a> (Business Email)</p>

<a href="https://gthz.it/ds"><img src="ds.png" width="48px" height="48px"></a>

<p> GiovsTechs#8806 </p>

<a href="https://gthz.it/mtg"><img src="tg.png" width="48px" heigth="48px"></a>

<p> @GiovanniTechHz</p>

<a href="https://gthz.it/ln"><img src="ln.png" width="48px" heigth="48px"></a>

<p>Giovanni Di Stazio</p>


---

Contact Form

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" />
<link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" />
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/tw-elements/dist/css/index.min.css" />
<script src="https://cdn.tailwindcss.com"></script>
<script>
  tailwind.config = {
    theme: {
      extend: {
        fontFamily: {
          sans: ['Inter', 'sans-serif'],
        },
      }
    }
  }
</script>
<div class="block p-6 rounded-lg shadow-lg bg-white max-w-md">
  <form action="https://hazentech.net/contact" method="post">
    <div class="form-group mb-6">
      <input type="text" class="form-control block
        w-full
        px-3
        py-1.5
        text-base
        font-normal
        text-gray-700
        bg-white bg-clip-padding
        border border-solid border-gray-300
        rounded
        transition
        ease-in-out
        m-0
        focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none" id="Name" name="firstname"
        placeholder="Name">
    </div>
        <div class="form-group mb-6">
      <input type="text" class="form-control block
        w-full
        px-3
        py-1.5
        text-base
        font-normal
        text-gray-700
        bg-white bg-clip-padding
        border border-solid border-gray-300
        rounded
        transition
        ease-in-out
        m-0
        focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none" id="Lastname" name="lastname"
        placeholder="Your LastName">
    </div>
    <div class="form-group mb-6">
      <input type="email" class="form-control block
        w-full
        px-3
        py-1.5
        text-base
        font-normal
        text-gray-700
        bg-white bg-clip-padding
        border border-solid border-gray-300
        rounded
        transition
        ease-in-out
        m-0
        focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none" id="email" name="email"
        placeholder="Email address">
    </div>
    <div class="form-group mb-6">
      <textarea
      class="
        form-control
        block
        w-full
        px-3
        py-1.5
        text-base
        font-normal
        text-gray-700
        bg-white bg-clip-padding
        border border-solid border-gray-300
        rounded
        transition
        ease-in-out
        m-0
        focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none
      "
      name="subject"
      id="subject"
      rows="3"
      placeholder="Message"
    ></textarea>
    </div>
    <div class="form-group form-check text-center mb-6">
    </div>
    <button type="submit" class="
      w-full
      px-6
      py-2.5
      bg-blue-600
      text-white
      font-medium
      text-xs
      leading-tight
      uppercase
      rounded
      shadow-md
      hover:bg-blue-700 hover:shadow-lg
      focus:bg-blue-700 focus:shadow-lg focus:outline-none focus:ring-0
      active:bg-blue-800 active:shadow-lg
      transition
      duration-150
      ease-in-out">Send</button>
  </form>
</div>
