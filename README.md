# englishwingsacademy
export default function SpokenEnglishWebsite() {
  const lessons = [
    {
      title: "Daily Greetings",
      example: "Good Morning! How are you?",
      telugu: "శుభోదయం! మీరు ఎలా ఉన్నారు?",
    },
    {
      title: "Self Introduction",
      example: "My name is Rahul. I study in 8th class.",
      telugu: "నా పేరు రాహుల్. నేను 8వ తరగతి చదువుతున్నాను.",
    },
    {
      title: "Classroom English",
      example: "May I come in, teacher?",
      telugu: "టీచర్, నేను లోపలికి రావచ్చా?",
    },
  ];

  return (
    <div className="min-h-screen bg-gradient-to-b from-blue-100 to-white text-gray-800">
      <header className="bg-blue-700 text-white py-6 shadow-lg">
        <div className="max-w-6xl mx-auto px-6 flex justify-between items-center">
          <div>
            <h1 className="text-4xl font-bold">English Wings Academy</h1>
            <p className="mt-2 text-lg">
              6th నుండి 10th క్లాస్ పిల్లల కోసం Smart Spoken English Learning Platform
            </p>
          </div>

          <button className="bg-yellow-400 text-black px-6 py-3 rounded-2xl font-semibold">
            Start Learning
          </button>
        </div>
      </header>

      <section className="max-w-6xl mx-auto px-6 py-16 grid md:grid-cols-2 gap-10 items-center">
        <div>
          <h2 className="text-5xl font-bold text-blue-800 leading-tight">
            Learn Spoken English Easily
          </h2>

          <p className="mt-6 text-lg leading-8">
            పిల్లలు సులభంగా ఇంగ్లీష్ మాట్లాడటం నేర్చుకునేలా రూపొందించిన వెబ్సైట్.
          </p>

          <div className="mt-8 flex gap-4">
            <button className="bg-blue-700 text-white px-6 py-3 rounded-2xl">
              Free Demo
            </button>

            <button className="border-2 border-blue-700 text-blue-700 px-6 py-3 rounded-2xl">
              Watch Videos
            </button>
          </div>
        </div>

        <div className="bg-white rounded-3xl shadow-2xl p-8">
          <h3 className="text-2xl font-bold text-center text-blue-700 mb-6">
            Today's Spoken English
          </h3>

          <div className="bg-blue-50 p-5 rounded-2xl">
            <p className="font-semibold text-lg">English:</p>
            <p className="text-2xl font-bold mt-2">
              How are you today?
            </p>
            <p className="mt-3 text-green-700 font-medium">
              తెలుగు: ఈ రోజు మీరు ఎలా ఉన్నారు?
            </p>
          </div>

          <button className="w-full mt-6 bg-green-500 text-white py-3 rounded-2xl text-lg font-semibold">
            Practice Pronunciation
          </button>
        </div>
      </section>

      <section className="max-w-6xl mx-auto px-6 py-10">
        <div className="text-center mb-12">
          <h2 className="text-4xl font-bold text-blue-800">Popular Lessons</h2>
        </div>

        <div className="grid md:grid-cols-3 gap-6">
          {lessons.map((lesson, index) => (
            <div
              key={index}
              className="bg-white rounded-3xl shadow-lg p-6 border border-gray-100"
            >
              <h3 className="text-2xl font-bold text-blue-700">
                {lesson.title}
              </h3>

              <p className="mt-4 text-lg font-medium text-gray-800">
                {lesson.example}
              </p>

              <p className="mt-3 text-green-700">{lesson.telugu}</p>

              <button className="mt-6 w-full bg-blue-600 text-white py-2 rounded-xl font-semibold">
                Learn Now
              </button>
            </div>
          ))}
        </div>
      </section>

      <section className="bg-white py-16">
        <div className="max-w-xl mx-auto bg-blue-50 rounded-3xl shadow-xl p-10">
          <h2 className="text-3xl font-bold text-center text-blue-800">
            Student Login
          </h2>

          <div className="mt-8 space-y-5">
            <input
              type="email"
              placeholder="Enter Email"
              className="w-full p-4 rounded-2xl border border-gray-300"
            />

            <input
              type="password"
              placeholder="Enter Password"
              className="w-full p-4 rounded-2xl border border-gray-300"
            />

            <button className="w-full bg-blue-700 text-white py-4 rounded-2xl text-lg font-semibold">
              Login
            </button>
          </div>
        </div>
      </section>

      <section className="max-w-5xl mx-auto px-6 py-16">
        <div className="bg-green-50 rounded-3xl shadow-xl p-10 text-center">
          <h2 className="text-4xl font-bold text-green-700">
            Real Audio Speaking Practice
          </h2>

          <button className="mt-8 bg-green-600 text-white px-8 py-4 rounded-2xl text-xl font-semibold">
            Start Speaking Practice
          </button>
        </div>
      </section>

      <section className="bg-red-50 py-16">
        <div className="max-w-6xl mx-auto px-6">
          <div className="text-center mb-12">
            <h2 className="text-4xl font-bold text-red-700">
              YouTube Video Lessons
            </h2>
          </div>

          <div className="grid md:grid-cols-3 gap-8">
            <div className="bg-white rounded-3xl shadow-lg p-6 text-center">
              <div className="text-5xl">▶️</div>
              <h3 className="text-2xl font-bold mt-4">Daily English</h3>
            </div>

            <div className="bg-white rounded-3xl shadow-lg p-6 text-center">
              <div className="text-5xl">▶️</div>
              <h3 className="text-2xl font-bold mt-4">Grammar Class</h3>
            </div>

            <div className="bg-white rounded-3xl shadow-lg p-6 text-center">
              <div className="text-5xl">▶️</div>
              <h3 className="text-2xl font-bold mt-4">Speaking Fluency</h3>
            </div>
          </div>
        </div>
      </section>

      <section className="max-w-6xl mx-auto px-6 py-16">
        <div className="bg-gray-900 text-white rounded-3xl shadow-2xl p-10">
          <h2 className="text-4xl font-bold text-center">Admin Dashboard</h2>

          <div className="grid md:grid-cols-4 gap-6 mt-10">
            <div className="bg-gray-800 p-6 rounded-2xl text-center">
              <h3 className="text-3xl font-bold">10000+</h3>
              <p className="mt-2">Students</p>
            </div>

            <div className="bg-gray-800 p-6 rounded-2xl text-center">
              <h3 className="text-3xl font-bold">1000+</h3>
              <p className="mt-2">Lessons</p>
            </div>

            <div className="bg-gray-800 p-6 rounded-2xl text-center">
              <h3 className="text-3xl font-bold">12</h3>
              <p className="mt-2">Courses</p>
            </div>

            <div className="bg-gray-800 p-6 rounded-2xl text-center">
              <h3 className="text-3xl font-bold">95%</h3>
              <p className="mt-2">Progress</p>
            </div>
          </div>
        </div>
      </section>

      <footer className="bg-blue-800 text-white py-10 mt-16">
        <div className="max-w-6xl mx-auto px-6 text-center">
          <h2 className="text-3xl font-bold">English Wings Academy</h2>
          <p className="mt-4 text-lg">
            Helping Students Speak English With Confidence
          </p>
        </div>
      </footer>
    </div>
  );
}
