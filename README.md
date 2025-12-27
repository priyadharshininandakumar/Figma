# Ex08 Event Registration Web Application
## Date:27.12.2025``

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
UI PAGE:
import { Button } from "./ui/button";
import { Card, CardContent } from "./ui/card";
import { Calendar, MapPin, User } from "lucide-react";

interface HomePageProps {
  onNavigate: (page: string) => void;
}

export function HomePage({ onNavigate }: HomePageProps) {
  return (
    <div className="min-h-screen bg-gradient-to-br from-blue-50 to-indigo-100">
      {/* Navigation */}
      <nav className="bg-white shadow-md">
        <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
          <div className="flex justify-between items-center h-16">
            <h1 className="text-indigo-600">Event Management System</h1>
            <div className="flex gap-6">
              <button
                onClick={() => onNavigate("home")}
                className="text-gray-700 hover:text-indigo-600 transition-colors"
              >
                Home
              </button>
              <button
                onClick={() => onNavigate("events")}
                className="text-gray-700 hover:text-indigo-600 transition-colors"
              >
                Events
              </button>
              <button
                onClick={() => onNavigate("register")}
                className="text-gray-700 hover:text-indigo-600 transition-colors"
              >
                Register
              </button>
            </div>
          </div>
        </div>
      </nav>

      {/* Hero Section */}
      <div className="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
        <div className="text-center mb-12">
          <h2 className="text-indigo-600 mb-4">Welcome to CodeFest 2026</h2>
          <p className="text-gray-600 max-w-2xl mx-auto">
            Join us for an exciting coding competition and tech event at Saveetha Engineering College, Chennai
          </p>
        </div>

        {/* Event Banner */}
        <Card className="mb-12 overflow-hidden bg-gradient-to-r from-indigo-500 to-purple-600 text-white">
          <CardContent className="p-8">
            <div className="grid md:grid-cols-2 gap-8">
              <div>
                <h3 className="mb-4 text-white">CodeFest 2026</h3>
                <div className="space-y-3">
                  <div className="flex items-center gap-3">
                    <Calendar className="w-5 h-5" />
                    <span>January 11, 2026</span>
                  </div>
                  <div className="flex items-center gap-3">
                    <MapPin className="w-5 h-5" />
                    <span>Majestorium Hall, Saveetha Engineering College, Chennai</span>
                  </div>
                  <div className="flex items-center gap-3">
                    <User className="w-5 h-5" />
                    <span>Coordinator: Jeevanantham C</span>
                  </div>
                </div>
              </div>
              <div className="flex flex-col justify-center gap-4">
                <p className="text-white/90">
                  Experience a day filled with coding challenges, networking opportunities, and technical workshops. Don't miss this opportunity to showcase your skills!
                </p>
                <div className="flex gap-4">
                  <Button
                    onClick={() => onNavigate("events")}
                    variant="secondary"
                    size="lg"
                  >
                    View Events
                  </Button>
                  <Button
                    onClick={() => onNavigate("register")}
                    variant="outline"
                    size="lg"
                    className="bg-white text-indigo-600 hover:bg-gray-100"
                  >
                    Register Now
                  </Button>
                </div>
              </div>
            </div>
          </CardContent>
        </Card>

        {/* Features */}
        <div className="grid md:grid-cols-3 gap-6">
          <Card>
            <CardContent className="p-6">
              <div className="text-indigo-600 mb-3"></div>
              <h4 className="mb-2">Competitions</h4>
              <p className="text-gray-600">
                Participate in exciting coding competitions and win amazing prizes
              </p>
            </CardContent>
          </Card>
          <Card>
            <CardContent className="p-6">
              <div className="text-indigo-600 mb-3"></div>
              <h4 className="mb-2">Workshops</h4>
              <p className="text-gray-600">
                Learn from industry experts through hands-on technical workshops
              </p>
            </CardContent>
          </Card>
          <Card>
            <CardContent className="p-6">
              <div className="text-indigo-600 mb-3"></div>
              <h4 className="mb-2">Networking</h4>
              <p className="text-gray-600">
                Connect with fellow developers and build lasting professional relationships
              </p>
            </CardContent>
          </Card>
        </div>
      </div>
    </div>
  );
}
```


## OUTPUT:
<img width="1919" height="1079" alt="Screenshot 2025-12-27 174109" src="https://github.com/user-attachments/assets/fe3b8238-adef-4743-b0e1-b9d575c982f0" />
<img width="1918" height="1075" alt="Screenshot 2025-12-27 174147" src="https://github.com/user-attachments/assets/50bb8ab6-f58b-4d08-9997-7f2944936f9f" />
<img width="1918" height="1078" alt="Screenshot 2025-12-27 174219" src="https://github.com/user-attachments/assets/3d0817a0-e441-4aa6-9036-2200462dc63f" />
<img width="1919" height="1078" alt="Screenshot 2025-12-27 174237" src="https://github.com/user-attachments/assets/05608db7-3ca3-4c2d-9320-4981537a232e" />




## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
