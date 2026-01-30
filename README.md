# ducnm.github.io
import { ImageWithFallback } from "@/app/components/figma/ImageWithFallback";

export default function App() {
  return (
    <div className="size-full relative">
      {/* Background Image */}
      <div className="absolute inset-0 z-0">
        <ImageWithFallback
          src="https://images.unsplash.com/photo-1765046255478-55efc763637c?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&ixid=M3w3Nzg4Nzd8MHwxfHNlYXJjaHwxfHxncmF5c2NhbGUlMjBhYnN0cmFjdCUyMG1pbmltYWx8ZW58MXx8fHwxNzY5NzM3ODc0fDA&ixlib=rb-4.1.0&q=80&w=1080&utm_source=figma&utm_medium=referral"
          alt="Background"
          className="w-full h-full object-cover opacity-30 grayscale"
        />
      </div>
      
      {/* Content */}
      <div className="relative z-10 size-full flex items-center justify-center px-8 py-12">
        <div className="w-full max-w-6xl flex gap-12">
          {/* Left Side - Main Content */}
          <div className="flex-1">
            <header className="mb-8">
              <h1 className="text-4xl mb-2 text-gray-900">Hello, I'm Đức, also goes by DaCoolGuy</h1>
              <p className="text-xl text-gray-800">Soon-to-be Software Engineer</p>
            </header>
            
            <div className="space-y-6 text-gray-900">
              <p>
                Welcome to my page! I'm a curious programmer striving to be one of the funnier software engineer out there.
                Just a guy who want to make games like those which lead him to this point.
              </p>
              <p>
                When I'm not coding, you can find me on a number of competitive game, or just relaxing with some casual games to pass the times.
              </p>
              
              <div>
                <h2 className="text-2xl mb-3 text-gray-900">Education</h2>
                <ul className="list-disc list-inside space-y-2">
                  <li>Post & Telecommunication Institute of Technology - Computer Science (2022-present)</li>
                  <li>Nguyen Hue High School for the Gifted - English Specialty (2019-2022)</li>
                </ul>
              </div>
              
              <div>
                <h2 className="text-2xl mb-3 text-gray-900">Coding Languages</h2>
                <ul className="list-disc list-inside space-y-2">
                  <li>C/C++</li>
                  <li>Python</li>
                  <li>Java</li>
                  <li>HTML & CSS</li>
                  <li>MySQL/SQL Server</li>
                </ul>
              </div>
            </div>
          </div>
          
          {/* Right Side - Contact Info */}
          <div className="w-80">
            <div className="bg-white/80 backdrop-blur-sm rounded-lg p-6 shadow-lg">
              <h2 className="text-2xl mb-4 text-gray-900">Contact</h2>
              <div className="space-y-3 text-gray-800">
                <div>
                  <p className="text-sm text-gray-600">Email</p>
                  <p>itsawilddcg@gmail.com</p>
                </div>
                <div>
                  <p className="text-sm text-gray-600">Phone</p>
                  <p>+1 (333) 727-3367</p>
                </div>
                <div>
                  <p className="text-sm text-gray-600">Location</p>
                  <p>Hanoi, Vietnam</p>
                </div>
                <div>
                  <p className="text-sm text-gray-600">Discord</p>
                  <p>itsawilddcg</p>
                </div>
                <div>
                  <p className="text-sm text-gray-600">GitHub</p>
                  <p>github.com/ItsAWildDCG</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  );
}
