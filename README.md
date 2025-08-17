# Uznura---landing-
import { motion } from "framer-motion";

export default function UznuraLanding() { return ( <div className="bg-[#0F172A] text-white font-sans"> {/* Hero Section */} <section className="min-h-screen flex flex-col justify-center items-center text-center p-6 bg-gradient-to-b from-[#0F172A] to-[#1E293B]"> <motion.h1 className="text-5xl md:text-7xl font-bold text-[#D4AF37]" initial={{ opacity: 0, y: -50 }} animate={{ opacity: 1, y: 0 }} transition={{ duration: 1 }} > UZNURA – Light of Heritage </motion.h1> <p className="mt-6 text-lg md:text-2xl max-w-2xl"> Illuminating the world through the art of craftsmanship </p> <motion.a href="#products" className="mt-10 px-6 py-3 bg-[#D4AF37] text-[#0F172A] rounded-2xl shadow-lg hover:bg-yellow-500 transition" whileHover={{ scale: 1.05 }} > Explore Our Collection </motion.a> </section>

{/* About Us */}
  <section id="about" className="py-20 px-6 md:px-20 bg-[#1E293B]">
    <h2 className="text-4xl font-bold text-[#D4AF37] mb-6">About Us</h2>
    <p className="max-w-3xl text-lg leading-relaxed">
      Uznura is the light shining from the heart of the ancient Silk Road to the modern world. For centuries, our artisans have combined patience, love, and artistry to create timeless, one-of-a-kind masterpieces.
    </p>
    <p className="mt-4 max-w-3xl text-lg">
      <strong>Our mission:</strong> to bring the rich heritage of Uzbekistan to the global stage and share it with international admirers.
    </p>
  </section>

  {/* Products */}
  <section id="products" className="py-20 px-6 md:px-20">
    <h2 className="text-4xl font-bold text-[#D4AF37] mb-10 text-center">
      Our Products
    </h2>
    <div className="grid md:grid-cols-3 gap-10">
      <motion.div
        whileHover={{ scale: 1.05 }}
        className="bg-[#1E293B] p-6 rounded-2xl shadow-lg"
      >
        <h3 className="text-2xl font-semibold mb-3">Handcrafted Jewelry</h3>
        <p>Gold, silver, and designs inspired by ancient patterns.</p>
      </motion.div>
      <motion.div
        whileHover={{ scale: 1.05 }}
        className="bg-[#1E293B] p-6 rounded-2xl shadow-lg"
      >
        <h3 className="text-2xl font-semibold mb-3">Natural Accessories</h3>
        <p>Crafted from silk, cotton, and genuine leather.</p>
      </motion.div>
      <motion.div
        whileHover={{ scale: 1.05 }}
        className="bg-[#1E293B] p-6 rounded-2xl shadow-lg"
      >
        <h3 className="text-2xl font-semibold mb-3">Cultural Home Décor</h3>
        <p>Ornaments and interior pieces adorned with traditional motifs.</p>
      </motion.div>
    </div>
    <p className="text-center mt-8 italic">
      Each product is a unique work of art.
    </p>
  </section>

  {/* Why Choose Us */}
  <section className="py-20 px-6 md:px-20 bg-[#1E293B]">
    <h2 className="text-4xl font-bold text-[#D4AF37] mb-6 text-center">
      Why Choose UZNURA?
    </h2>
    <ul className="max-w-3xl mx-auto text-lg space-y-3 list-disc list-inside">
      <li>Exclusive craftsmanship – no two pieces are ever the same.</li>
      <li>Uzbek heritage – infused with history and culture.</li>
      <li>Premium quality – natural materials & master artisanship.</li>
      <li>Worldwide delivery – fast and reliable shipping to any corner of the globe.</li>
    </ul>
  </section>

  {/* Vision */}
  <section className="py-20 px-6 md:px-20 text-center">
    <h2 className="text-4xl font-bold text-[#D4AF37] mb-6">Our Vision</h2>
    <blockquote className="italic text-xl max-w-2xl mx-auto">
      “We share the beauty created by artisans’ hands with the world. Each product is an expression of history, culture, and love.”
    </blockquote>
  </section>

  {/* Call to Action */}
  <section className="py-20 px-6 md:px-20 bg-[#1E293B] text-center">
    <h2 className="text-3xl font-bold mb-6 text-[#D4AF37]">Join Us!</h2>
    <p className="text-lg max-w-xl mx-auto">
      Wherever you are in the world, <span className="text-[#D4AF37] font-semibold">UZNURA</span> brings you light and inspiration.
    </p>
    <motion.a
      href="#"
      className="mt-10 inline-block px-8 py-4 bg-[#D4AF37] text-[#0F172A] rounded-2xl shadow-lg hover:bg-yellow-500 transition font-semibold"
      whileHover={{ scale: 1.05 }}
    >
      Order Now
    </motion.a>
  </section>

  {/* Footer */}
  <footer className="py-10 text-center text-sm bg-[#0F172A] border-t border-gray-700">
    © {new Date().getFullYear()} UZNURA. All rights reserved.
  </footer>
</div>

); }

