# footer
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://fonts.googleapis.com/css2?family=Lexend+Deca:wght@400;600;700&display=swap" rel="stylesheet">
<script src="https://cdn.tailwindcss.com"></script>
<script>
    tailwind.config = {
      theme: {
        fontFamily: {
          lexend: ["Lexend Deca", "sans-serif"],
        },
        extend: {
          spacing: {
            30: "30px",
            60: "60px",
            100: "100px",
            140: "140px",
          },
          backgroundImage: {
            hero: "url('images/hero.png')",
          },
          colors: {
            primary: "#30b0ae",
            secondary: "#5468E7",
            inputBorder: "#D1ECFD",
          },
        },
      },
    };
  </script>
    <title>Document</title>
</head>
<body>
    <footer
      class="bg-primary flex flex-col gap-[56px] md:gap-12 xl:px-140 px-6 sm:px-[40px] text-white pt-12 md:pt-[72px] xl:pt-24 pb-10"
    >
      <div class="w-fit grid sm:grid-cols-3 xl:grid-cols-5 gap-6">
        <div class="w-[170px] sm:col-span-3 xl:col-span-1">
          <h1 class="font-semibold text-white text-5xl">
            team<span class="text-secondary">.</span>
          </h1>
          <p>Collaboration platform for mordern team</p>
        </div>
        <ul
          class="space-y-4 font-normal leading-[23px] text-[14px] tracking-tighter"
        >
          <li class="text-secondary text-[24px] leading-30">Company</li>
          <li>Product</li>
          <li>Blog</li>
          <li>Support</li>
        </ul>
        <ul
          class="space-y-4 font-normal leading-[23px] text-[14px] tracking-tighter"
        >
          <li class="text-secondary text-[24px] leading-30">Features</li>
          <li>Screen Sharing</li>
          <li>iOS & Android Apps</li>
          <li>File Sharing</li>
          <li>User Managment</li>
        </ul>
        <ul
          class="space-y-4 font-normal leading-[23px] text-[14px] tracking-tighter"
        >
          <li class="text-secondary text-[24px] leading-30">Contact Us</li>
          <li>Contact Us</li>
          <li>info@teamapp.com</li>
          <li>1-800-200-300</li>
          <li>1010 Sunset Blv. Palo Alto, California</li>
        </ul>
        <ul
          class="space-y-4 font-normal leading-[23px] text-[14px] tracking-tighter"
        >
          <li class="text-secondary text-[24px] leading-30">Stay up to date</li>
          <li>Subscribe to our newseller</li>
          <li>
            <div
              class="w-[268px] flex justify-between bg-[#f5f5f5] py-[11px] px-4 rounded border-inputBorder"
            >
              <input
                type="email"
                placeholder="Email"
                class="border-none bg-inherit"
              />
              <img src="https://i.postimg.cc/ydGK4Yx3/arrow.png" alt="arrow" />
            </div>
          </li>
        </ul>
      </div>
      <p>Â© Copyright Team Inc.</p>
    </footer>
    
</body>
</html>
