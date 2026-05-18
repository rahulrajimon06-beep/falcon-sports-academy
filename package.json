export default function FalconSportsAcademy() {
  const events = [
    "Football",
    "Cricket",
    "Volleyball",
    "Badminton",
    "Roller Skating",
    "Boxing",
    "Athletics",
  ];

  return (
    <div className="min-h-screen bg-[#0d1b12] text-white font-sans">
      {/* HERO SECTION */}
      <section
        className="relative h-screen flex items-center justify-center bg-cover bg-center"
        style={{
          backgroundImage:
            "url('https://images.unsplash.com/photo-1508098682722-e99c43a406b2?q=80&w=1600&auto=format&fit=crop')",
        }}
      >
        <div className="absolute inset-0 bg-black/60"></div>

        {/* Hero Content */}
        <div className="relative z-10 text-center px-6 max-w-5xl">
          <div className="flex justify-center mb-8">
            <div className="bg-white/10 backdrop-blur-md p-5 rounded-full border border-yellow-500/40 shadow-2xl">
              <img
                src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMgAAABPCAYAAACB5fQwAAAACXBIWXMAAAsSAAALEgHS3X78AAAgAElEQVR4nO2deXhU1fnHP3fPTHYmyU7YkAQISwgQSLAHEFRKq9JCV0VR3Lq1tVpr1Vq7W1vXWq2t1tZaa7VWW2ut1lr7q1Vxq0gRkYQskIQN2ZlkJ2fO74+ZmWQmM5P5fD7n+Xye85zznOc5c+4553znnOc5Q0RERERERERERET0X7iP9wAiIiIiIiIiIiKi9yYJQURERERERERERPQ+SQgiIiIiIiIiIiKi+0lCEBEREREREREREd3/JCFIiIiIiIiIiIiI7n+SEE..."
                alt="Falcon Sports Academy Logo"
                className="w-24 h-24 object-contain"
              />
            </div>
          </div>

          <h1 className="text-5xl md:text-7xl font-extrabold tracking-[0.2em] mb-6 text-yellow-400 drop-shadow-2xl italic uppercase">
            FALCON SPORTS ACADEMY
          </h1>

          <p className="text-xl md:text-3xl font-light text-gray-100 mb-8 leading-relaxed">
            Inspiring the Future of Sports
          </p>

          <p className="max-w-3xl mx-auto text-gray-200 text-lg leading-8 mb-10">
            Building champions through discipline, determination, and development.
          </p>

          <div className="flex flex-wrap justify-center gap-5">
            <a
              href="#about"
              className="bg-yellow-500 hover:bg-yellow-400 text-black font-bold px-8 py-4 rounded-2xl shadow-2xl transition"
            >
              Explore Academy
            </a>

            <a
              href="#contact"
              className="border border-yellow-500 hover:bg-yellow-500/20 px-8 py-4 rounded-2xl font-semibold transition"
            >
              Contact Us
            </a>
          </div>
        </div>
      </section>

      {/* NAVBAR */}
      <nav className="sticky top-0 z-50 bg-[#08110b]/95 backdrop-blur-md border-b border-yellow-500/20">
        <div className="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
          <h2 className="text-2xl font-bold text-yellow-400">
            FSA
          </h2>

          <div className="flex gap-6 text-sm md:text-base text-gray-200">
            <a href="#about" className="hover:text-yellow-400 transition">About</a>
            <a href="#purpose" className="hover:text-yellow-400 transition">Purpose</a>
            <a href="#events" className="hover:text-yellow-400 transition">Events</a>
            <a href="#vision" className="hover:text-yellow-400 transition">Vision</a>
            <a href="#mission" className="hover:text-yellow-400 transition">Mission</a>
            <a href="#gallery" className="hover:text-yellow-400 transition">Gallery</a>
            <a href="#locations" className="hover:text-yellow-400 transition">Locations</a>
            <a href="#contact" className="hover:text-yellow-400 transition">Contact</a>
          </div>
        </div>
      </nav>

      {/* ABOUT */}
      <section id="about" className="py-24 px-6 bg-[#102117]">
        <div className="max-w-7xl mx-auto grid md:grid-cols-2 gap-14 items-center">
          <div>
            <img
              src="https://images.unsplash.com/photo-1517649763962-0c623066013b?q=80&w=1400&auto=format&fit=crop"
              alt="Football Training"
              className="rounded-3xl shadow-2xl border border-yellow-500/20"
            />
          </div>

          <div>
            <h2 className="text-5xl font-black text-yellow-400 mb-8">
              About Us
            </h2>

            <p className="text-lg text-gray-300 leading-9 mb-6">
              Falcon Sports Academy (FSA) is a professional multi-sports institution committed to grassroots development and nurturing the next generation of athletes.
            </p>

            <p className="text-lg text-gray-300 leading-9 mb-6">
              Based on the values of discipline, determination, and development, FSA provides a dynamic environment where talent is identified, honed, and empowered.
            </p>

            <p className="text-lg text-gray-300 leading-9">
              We specialize in conducting multiple sports events including football, athletics, cricket, volleyball, badminton, boxing, roller skating, and more.
            </p>
          </div>
        </div>
      </section>

      {/* PURPOSE */}
      <section id="purpose" className="py-24 px-6 bg-[#0d1b12]">
        <div className="max-w-6xl mx-auto text-center">
          <h2 className="text-5xl font-black text-yellow-400 mb-14">
            Our Purpose
          </h2>

          <div className="grid md:grid-cols-2 gap-8 text-left">
            {[
              "To nurture young talent through professional and scientific training",
              "To promote physical literacy and overall well-being",
              "To build sports as a career pathway for youth",
              "To create a strong community rooted in sports values and teamwork",
            ].map((item, index) => (
              <div
                key={index}
                className="bg-[#16281d] border border-yellow-500/20 p-8 rounded-3xl shadow-xl hover:-translate-y-2 transition"
              >
                <p className="text-lg text-gray-200 leading-8">{item}</p>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* EVENTS */}
      <section id="events" className="py-24 px-6 bg-[#102117]">
        <div className="max-w-7xl mx-auto text-center">
          <h2 className="text-5xl font-black text-yellow-400 mb-16">
            Sports Events
          </h2>

          <div className="grid grid-cols-2 md:grid-cols-4 gap-8">
            {events.map((sport, index) => (
              <div
                key={index}
                className="bg-[#182c21] border border-yellow-500/20 rounded-3xl p-10 shadow-2xl hover:scale-105 transition"
              >
                <h3 className="text-2xl font-bold text-white">{sport}</h3>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* VISION */}
      <section id="vision" className="py-24 px-6 bg-[#0d1b12] text-center">
        <div className="max-w-5xl mx-auto">
          <h2 className="text-5xl font-black text-yellow-400 mb-10">
            Our Vision
          </h2>

          <p className="text-xl text-gray-300 leading-10">
            To be a leading force in Indian grassroots sports, producing top-tier athletes and creating an inclusive platform for all to explore their sporting potential.
          </p>
        </div>
      </section>

      {/* MISSION */}
      <section id="mission" className="py-24 px-6 bg-[#102117]">
        <div className="max-w-6xl mx-auto text-center">
          <h2 className="text-5xl font-black text-yellow-400 mb-16">
            Our Mission
          </h2>

          <div className="grid md:grid-cols-2 gap-8 text-left">
            {[
              "Deliver high-quality, consistent sports coaching",
              "Host competitive, well-managed multi-sports events",
              "Partner with schools and communities for greater sports exposure",
              "Encourage holistic development through sportsmanship and fitness",
            ].map((item, index) => (
              <div
                key={index}
                className="bg-[#182c21] border border-yellow-500/20 p-8 rounded-3xl"
              >
                <p className="text-lg text-gray-200 leading-8">{item}</p>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* WHY CHOOSE */}
      <section className="py-24 px-6 bg-[#0d1b12]">
        <div className="max-w-7xl mx-auto">
          <h2 className="text-5xl font-black text-yellow-400 text-center mb-16">
            Why Choose FSA?
          </h2>

          <div className="grid md:grid-cols-2 gap-8">
            {[
              "Multi-Sport Focus with certified coaches and specialized modules.",
              "Experienced team of professionals, athletes, and sports educators.",
              "Career-oriented guidance including tournaments and trials.",
              "Community-driven programs reaching rural and underserved areas.",
              "Professionally managed events that build confidence and competitive spirit.",
            ].map((item, index) => (
              <div
                key={index}
                className="bg-[#16281d] border border-yellow-500/20 p-8 rounded-3xl shadow-xl"
              >
                <p className="text-lg text-gray-200 leading-8">{item}</p>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* GALLERY */}
      <section id="gallery" className="py-24 px-6 bg-[#102117]">
        <div className="max-w-7xl mx-auto text-center">
          <h2 className="text-5xl font-black text-yellow-400 mb-16">
            Gallery
          </h2>

          <div className="grid md:grid-cols-3 gap-8">
            {[
              "football training",
              "athletics running",
              "sports academy",
              "football field",
              "boxing training",
              "volleyball sports",
            ].map((item, index) => (
              <img
                key={index}
                src={`https://source.unsplash.com/800x600/?${item}`}
                alt={item}
                className="rounded-3xl shadow-2xl hover:scale-105 transition duration-300 border border-yellow-500/20"
              />
            ))}
          </div>
        </div>
      </section>

      {/* LOCATIONS */}
      <section id="locations" className="py-24 px-6 bg-[#0d1b12]">
        <div className="max-w-6xl mx-auto text-center">
          <h2 className="text-5xl font-black text-yellow-400 mb-16">
            Our Locations
          </h2>

          <div className="grid md:grid-cols-3 gap-8">
            {[
              {
                school: "Georgian Public School",
                place: "Edathua, Alappuzha",
              },
              {
                school: "Devi Vilasam Higher Secondary School",
                place: "Kandankary",
              },
              {
                school: "SH School",
                place: "Changanacherry",
              },
            ].map((location, index) => (
              <div
                key={index}
                className="bg-[#16281d] border border-yellow-500/20 rounded-3xl p-10 shadow-2xl hover:-translate-y-2 transition"
              >
                <h3 className="text-2xl font-bold text-yellow-400 mb-4">
                  {location.school}
                </h3>

                <p className="text-lg text-gray-300 leading-8">
                  📍 {location.place}
                </p>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* CONTACT */}
      <section id="contact" className="py-24 px-6 bg-[#0d1b12]">
        <div className="max-w-5xl mx-auto text-center">
          <h2 className="text-5xl font-black text-yellow-400 mb-10">
            Contact Us
          </h2>

          <p className="text-2xl text-gray-300 mb-6">
            Join Falcon Sports Academy — where champions are made!
          </p>

          <div className="bg-[#16281d] border border-yellow-500/20 rounded-3xl p-12 mt-12 shadow-2xl">
            <div className="space-y-6 text-lg text-gray-200">
              <p>
                📞 <span className="font-semibold text-yellow-400">9087654321</span>
              </p>

              <p>
                📧 falconsports2025@gmail.com
              </p>

              <p>
                🌐 www.falconsportsacademy.com
              </p>
            </div>

            <div className="mt-12 grid gap-4">
              <input
                type="text"
                placeholder="Your Name"
                className="w-full bg-[#0d1b12] border border-yellow-500/20 rounded-xl px-5 py-4"
              />

              <input
                type="email"
                placeholder="Your Email"
                className="w-full bg-[#0d1b12] border border-yellow-500/20 rounded-xl px-5 py-4"
              />

              <textarea
                rows="5"
                placeholder="Your Message"
                className="w-full bg-[#0d1b12] border border-yellow-500/20 rounded-xl px-5 py-4"
              ></textarea>

              <button className="bg-yellow-500 hover:bg-yellow-400 text-black font-bold py-4 rounded-2xl transition mt-4">
                Send Message
              </button>
            </div>
          </div>
        </div>
      </section>

      {/* FOOTER */}
      <footer className="bg-[#08110b] border-t border-yellow-500/10 py-8 text-center text-gray-400">
        © 2026 Falcon Sports Academy. All Rights Reserved.
      </footer>
    </div>
  );
}
