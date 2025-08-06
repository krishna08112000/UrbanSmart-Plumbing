Of course\! Adding social media icons to the footer is a great way to connect with your customers.

I have updated the HTML code to include links for Facebook, Instagram, and YouTube in the footer. The icons will appear next to the copyright notice and are styled to match your website's design.

Just remember to replace the placeholder `href="#"` with your actual social media profile URLs.

Here is the complete updated code:

```html
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UrbanSmart Plumbing - Professional Plumbing Services in Balaghat</title>
    
    <script src="https://cdn.tailwindcss.com"></script>
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">

    <style>
        /* Applying Poppins font to the entire body */
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #f8fafc; /* Light gray background */
        }
        /* Custom styles for active tab */
        .tab-active {
            background-color: #0284c7; /* Sky 700 */
            color: white;
            border-color: #0284c7;
        }
        /* Custom styles for inactive tabs */
        .tab-inactive {
            background-color: white;
            color: #374151; /* Gray 700 */
            border-color: #e5e7eb; /* Gray 200 */
        }
        /* Style for the hero section background */
        .hero-bg {
            background-image: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('https://placehold.co/1200x800/e2e8f0/334155?text=Modern+Bathroom');
            background-size: cover;
            background-position: center;
        }
    </style>
</head>
<body class="text-gray-800">

    <header class="bg-white shadow-md sticky top-0 z-50">
        <nav class="container mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-sky-700">
                UrbanSmart Plumbing
            </a>
            <div class="hidden md:flex items-center space-x-6">
                <a href="#services" class="text-gray-600 hover:text-sky-600 transition duration-300">Services</a>
                <a href="#rates" class="text-gray-600 hover:text-sky-600 transition duration-300">Rate List</a>
                <a href="#contact" class="text-gray-600 hover:text-sky-600 transition duration-300">Contact</a>
            </div>
            <a href="#contact" class="hidden md:inline-block bg-orange-500 text-white font-semibold px-5 py-2 rounded-lg hover:bg-orange-600 transition duration-300">
                Book Service
            </a>
            <button id="mobile-menu-button" class="md:hidden text-gray-700 focus:outline-none">
                <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
            </button>
        </nav>
        <div id="mobile-menu" class="hidden md:hidden px-6 pt-2 pb-4">
            <a href="#services" class="block py-2 text-gray-600 hover:text-sky-600">Services</a>
            <a href="#rates" class="block py-2 text-gray-600 hover:text-sky-600">Rate List</a>
            <a href="#contact" class="block py-2 text-gray-600 hover:text-sky-600">Contact</a>
            <a href="#contact" class="block mt-2 w-full text-center bg-orange-500 text-white font-semibold px-5 py-2 rounded-lg hover:bg-orange-600">
                Book Service
            </a>
        </div>
    </header>

    <main>
        <section class="hero-bg text-white py-20 md:py-32">
            <div class="container mx-auto px-6 text-center">
                <h1 class="text-4xl md:text-6xl font-bold mb-4 leading-tight">Your Trusted Plumbing Partner in Balaghat</h1>
                <p class="text-lg md:text-xl text-gray-200 mb-8 max-w-3xl mx-auto">Professional solutions for every leak, clog, and installation. Reliable service by Krishna Yadav.</p>
                <div class="flex justify-center items-center space-x-4">
                    <a href="#rates" class="bg-sky-600 text-white font-semibold px-8 py-3 rounded-lg hover:bg-sky-700 transition duration-300">View Rate List</a>
                    <a href="#contact" class="bg-white text-sky-700 font-semibold px-8 py-3 rounded-lg hover:bg-gray-200 transition duration-300">Contact Us</a>
                </div>
            </div>
        </section>

        <section class="py-16 bg-white">
            <div class="container mx-auto px-6">
                <h2 class="text-3xl font-bold text-center mb-10">Why Choose UrbanSmart Plumbing?</h2>
                <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                    <div class="text-center p-6 border border-gray-200 rounded-lg shadow-sm hover:shadow-lg transition">
                        <div class="flex items-center justify-center h-16 w-16 rounded-full bg-sky-100 mx-auto mb-4">
                             <svg class="w-8 h-8 text-sky-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.02 12.02 0 003 9c0 5.591 3.824 10.29 9 11.622 5.176-1.332 9-6.03 9-11.622 0-1.042-.133-2.052-.382-3.016z"></path></svg>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Licensed Professionals</h3>
                        <p class="text-gray-600">Our team, led by Krishna Yadav, consists of certified and experienced plumbers.</p>
                    </div>
                    <div class="text-center p-6 border border-gray-200 rounded-lg shadow-sm hover:shadow-lg transition">
                        <div class="flex items-center justify-center h-16 w-16 rounded-full bg-sky-100 mx-auto mb-4">
                            <svg class="w-8 h-8 text-sky-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 9V7a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2m2 4h10a2 2 0 002-2v-6a2 2 0 00-2-2H9a2 2 0 00-2 2v6a2 2 0 002 2zm7-5a2 2 0 11-4 0 2 2 0 014 0z"></path></svg>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Transparent Pricing</h3>
                        <p class="text-gray-600">No hidden costs. Check our detailed rate list before you book. Free inspection in Balaghat.</p>
                    </div>
                    <div class="text-center p-6 border border-gray-200 rounded-lg shadow-sm hover:shadow-lg transition">
                        <div class="flex items-center justify-center h-16 w-16 rounded-full bg-sky-100 mx-auto mb-4">
                            <svg class="w-8 h-8 text-sky-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Emergency Service</h3>
                        <p class="text-gray-600">We are available for urgent plumbing needs. Just give us a call.</p>
                    </div>
                    <div class="text-center p-6 border border-gray-200 rounded-lg shadow-sm hover:shadow-lg transition">
                        <div class="flex items-center justify-center h-16 w-16 rounded-full bg-sky-100 mx-auto mb-4">
                           <svg class="w-8 h-8 text-sky-600" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 10h4.764a2 2 0 011.789 2.894l-3.5 7A2 2 0 0115.263 21h-4.017c-.163 0-.326-.02-.485-.06L7 20m7-10V5a2 2 0 00-2-2h-.085a2 2 0 00-1.736.97l-2.7 5.4a2 2 0 001.736 3.03h4.017z"></path></svg>
                        </div>
                        <h3 class="text-xl font-semibold mb-2">Satisfaction Guaranteed</h3>
                        <p class="text-gray-600">We stand by the quality of our work and ensure you are 100% satisfied.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="services" class="py-16">
            <div class="container mx-auto px-6">
                <h2 class="text-3xl font-bold text-center mb-10">Our Core Services</h2>
                <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                    <div class="bg-white p-6 rounded-lg shadow-md">
                        <h3 class="font-semibold text-xl mb-2">Pipe Fitting & Layouts</h3>
                        <p class="text-gray-600">Expert fitting for UPVC, CPVC, SWR, and rainwater pipes for new constructions and renovations.</p>
                    </div>
                    <div class="bg-white p-6 rounded-lg shadow-md">
                        <h3 class="font-semibold text-xl mb-2">Bathroom & Kitchen Plumbing</h3>
                        <p class="text-gray-600">Complete fitting for taps, showers, sinks, commodes, and geysers, from basic to luxury setups.</p>
                    </div>
                    <div class="bg-white p-6 rounded-lg shadow-md">
                        <h3 class="font-semibold text-xl mb-2">Leakage Repair</h3>
                        <p class="text-gray-600">Quick detection and repair of minor and major leakages in walls, floors, and fixtures.</p>
                    </div>
                    <div class="bg-white p-6 rounded-lg shadow-md">
                        <h3 class="font-semibold text-xl mb-2">Drainage Unclogging</h3>
                        <p class="text-gray-600">Effective solutions for clearing blocked drainage lines in kitchens and bathrooms.</p>
                    </div>
                     <div class="bg-white p-6 rounded-lg shadow-md">
                        <h3 class="font-semibold text-xl mb-2">Installation Services</h3>
                        <p class="text-gray-600">Professional installation of water tanks, motors, pumps, RO filters, and geysers.</p>
                    </div>
                     <div class="bg-white p-6 rounded-lg shadow-md">
                        <h3 class="font-semibold text-xl mb-2">Emergency Visits</h3>
                        <p class="text-gray-600">Fast and reliable service for any urgent plumbing issue you might face.</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="rates" class="py-16 bg-white">
            <div class="container mx-auto px-6">
                <h2 class="text-3xl font-bold text-center mb-4">Transparent Rate List (2025)</h2>
                <p class="text-center text-gray-600 mb-10">All rates are for labor charges only. Material cost is extra. Final rate confirmed after site visit.</p>
                
                <div class="flex flex-wrap justify-center mb-8 border-b border-gray-200">
                    <button class="tab-button tab-active py-2 px-6 font-semibold border-b-2" onclick="openTab(event, 'general')">General Services</button>
                    <button class="tab-button tab-inactive py-2 px-6 font-semibold border-b-2" onclick="openTab(event, 'bathroom')">Bathroom Plumbing</button>
                    <button class="tab-button tab-inactive py-2 px-6 font-semibold border-b-2" onclick="openTab(event, 'pipe')">Pipe Fitting</button>
                </div>

                <div id="general" class="tab-content">
                    <div class="overflow-x-auto">
                        <table class="min-w-full bg-white rounded-lg shadow">
                            <thead class="bg-sky-600 text-white">
                                <tr>
                                    <th class="text-left py-3 px-4 uppercase font-semibold text-sm">Service</th>
                                    <th class="text-left py-3 px-4 uppercase font-semibold text-sm">Starting Rate (INR)</th>
                                </tr>
                            </thead>
                            <tbody class="text-gray-700">
                                <tr><td class="text-left py-3 px-4">Pipe Fitting (per point)</td><td class="text-left py-3 px-4">₹200 – ₹300</td></tr>
                                <tr class="bg-gray-50"><td class="text-left py-3 px-4">Bathroom Fitting (full set)</td><td class="text-left py-3 px-4">₹8,000 – ₹10,000</td></tr>
                                <tr><td class="text-left py-3 px-4">Kitchen Sink + Tap Installation</td><td class="text-left py-3 px-4">₹1,000 – ₹2,000</td></tr>
                                <tr class="bg-gray-50"><td class="text-left py-3 px-4">Water Tank Installation</td><td class="text-left py-3 px-4">₹600 – ₹1,000</td></tr>
                                <tr><td class="text-left py-3 px-4">Water Motor (Pump) Installation</td><td class="text-left py-3 px-4">₹1,000 – ₹1,200</td></tr>
                                <tr class="bg-gray-50"><td class="text-left py-3 px-4">Leakage Detection & Minor Repair</td><td class="text-left py-3 px-4">₹300 – ₹500</td></tr>
                                <tr><td class="text-left py-3 px-4">Major Leakage Repair (wall/floor)</td><td class="text-left py-3 px-4">₹800 – ₹1,500</td></tr>
                                <tr class="bg-gray-50"><td class="text-left py-3 px-4">Drainage Line Unclogging (Minor)</td><td class="text-left py-3 px-4">₹800 – ₹1,000</td></tr>
                                <tr><td class="text-left py-3 px-4">Drainage Repair (Major)</td><td class="text-left py-3 px-4">₹2,000 – ₹3,000</td></tr>
                                <tr class="bg-gray-50"><td class="text-left py-3 px-4">Geyser Plumbing Setup</td><td class="text-left py-3 px-4">₹600 – ₹1,000</td></tr>
                                <tr><td class="text-left py-3 px-4">RO / Water Filter Installation</td><td class="text-left py-3 px-4">₹300 – ₹500</td></tr>
                                <tr class="bg-orange-100 text-orange-800 font-semibold"><td class="text-left py-3 px-4">Emergency Plumbing Visit (Urgent)</td><td class="text-left py-3 px-4">₹200 extra per call</td></tr>
                            </tbody>
                        </table>
                    </div>
                </div>

                <div id="bathroom" class="tab-content" style="display:none;">
                    <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
                        <div class="border rounded-lg p-4 shadow-sm">
                            <h4 class="font-bold text-lg mb-2">1. Common Bathroom</h4>
                            <p class="text-sm text-gray-600 mb-3">Standard fitting for basic homes (3-4 points).</p>
                            <ul class="text-sm space-y-1">
                                <li>Tap + Shower + Washbasin: ₹1500–₹2000</li>
                                <li>CPVC Pipe Layout: ₹2500–₹3000</li>
                                <li>Geyser Connection: ₹600–₹1000</li>
                            </ul>
                            <p class="mt-3 font-bold text-sky-700">Total Approx: ₹4000–₹5000</p>
                        </div>
                         <div class="border rounded-lg p-4 shadow-sm">
                            <h4 class="font-bold text-lg mb-2">2. Master Bathroom</h4>
                            <p class="text-sm text-gray-600 mb-3">Attached bathroom with geyser, flush tank (5-6 points).</p>
                             <ul class="text-sm space-y-1">
                                <li>Full Bathroom Layout: ₹4000–₹5000</li>
                                <li>CPVC Hot/Cold Line: ₹2500–₹3000</li>
                                <li>Flush Tank & Commode: ₹800–₹1000</li>
                            </ul>
                            <p class="mt-3 font-bold text-sky-700">Total Approx: ₹7000–₹8500</p>
                        </div>
                         <div class="border rounded-lg p-4 shadow-sm">
                            <h4 class="font-bold text-lg mb-2">3. Luxury Bathroom</h4>
                            <p class="text-sm text-gray-600 mb-3">Hotel/bungalow standard with concealed fittings.</p>
                             <ul class="text-sm space-y-1">
                                <li>Concealed Pipework: ₹4000–₹6000</li>
                                <li>Shower Panel Setup: ₹1500–₹2500</li>
                                <li>Designer Tap Install: ₹1200–₹2000</li>
                            </ul>
                            <p class="mt-3 font-bold text-sky-700">Total Approx: ₹8000–₹12,000+</p>
                        </div>
                         <div class="border rounded-lg p-4 shadow-sm">
                            <h4 class="font-bold text-lg mb-2">4. BISS Bathroom</h4>
                            <p class="text-sm text-gray-600 mb-3">Budget Indian Smart Setup for rentals, shops.</p>
                             <ul class="text-sm space-y-1">
                                <li>CPVC Water Line (3-point): ₹2200–₹2600</li>
                                <li>Basic Tap, Shower, Flush: ₹2000–₹2300</li>
                            </ul>
                            <p class="mt-3 font-bold text-sky-700">Total Approx: ₹4000–₹4900</p>
                        </div>
                    </div>
                </div>

                <div id="pipe" class="tab-content" style="display:none;">
                     <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
                        <div class="border rounded-lg p-4 shadow-sm">
                            <h4 class="font-bold text-lg mb-2">1. UPVC Pipe Fitting</h4>
                            <p class="text-sm text-gray-600 mb-3">For cold water supply & outdoor plumbing.</p>
                            <ul class="text-sm space-y-1">
                                <li>Laying (per point): ₹250–₹400</li>
                                <li>Tank to Tap: ₹400–₹600</li>
                                <li>Complete Home Layout: ₹3000–₹5000</li>
                            </ul>
                        </div>
                        <div class="border rounded-lg p-4 shadow-sm">
                            <h4 class="font-bold text-lg mb-2">2. CPVC Pipe Fitting</h4>
                            <p class="text-sm text-gray-600 mb-3">For hot & cold water supply (geyser, etc).</p>
                             <ul class="text-sm space-y-1">
                                <li>Laying (per point): ₹300–₹450</li>
                                <li>Geyser Line Setup: ₹500–₹700</li>
                                <li>Bathroom Layout: ₹1500–₹2500</li>
                            </ul>
                        </div>
                        <div class="border rounded-lg p-4 shadow-sm">
                            <h4 class="font-bold text-lg mb-2">3. SWR Pipe Fitting</h4>
                            <p class="text-sm text-gray-600 mb-3">For drainage, sewer & waste water lines.</p>
                             <ul class="text-sm space-y-1">
                                <li>Laying (per meter): ₹150–₹300</li>
                                <li>Drainage Trap Install: ₹300–₹500</li>
                                <li>Manhole Fitting: ₹600–₹900</li>
                            </ul>
                        </div>
                        <div class="border rounded-lg p-4 shadow-sm">
                            <h4 class="font-bold text-lg mb-2">4. Rainwater Pipe Fitting</h4>
                            <p class="text-sm text-gray-600 mb-3">For roof drainage and harvesting.</p>
                             <ul class="text-sm space-y-1">
                                <li>Vertical Downpipe: ₹300–₹500</li>
                                <li>Balcony Outlet: ₹400–₹700</li>
                                <li>Harvesting Connection: ₹800–₹1200</li>
                            </ul>
                        </div>
                    </div>
                </div>

            </div>
        </section>

        <section id="contact" class="py-16">
            <div class="container mx-auto px-6">
                <div class="bg-white rounded-lg shadow-xl p-8 md:p-12 lg:flex lg:items-center lg:justify-between">
                    <div class="lg:w-1/2 mb-10 lg:mb-0">
                        <h2 class="text-3xl font-bold mb-2">Book a Service or Get a Quote</h2>
                        <p class="text-gray-600 mb-6">Fill out the form or call us directly for immediate assistance. We're here to help!</p>
                        <div class="space-y-4">
                            <div class="flex items-center">
                                <svg class="w-6 h-6 text-sky-600 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path></svg>
                                <a href="tel:+917489077309" class="text-lg font-semibold text-gray-800 hover:text-sky-600">+91-74890 77309</a>
                            </div>
                            <div class="flex items-center">
                                <svg class="w-6 h-6 text-sky-600 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path></svg>
                                <span class="text-lg text-gray-800">Balaghat, Madhya Pradesh</span>
                            </div>
                        </div>
                         <p class="mt-6 text-sm italic text-gray-500">Quick Service | Sahi Daam | Vishwas ke Saath</p>
                    </div>
                    <div class="lg:w-1/2">
                        <form action="#" method="POST" class="space-y-4">
                            <div>
                                <label for="name" class="sr-only">Name</label>
                                <input type="text" name="name" id="name" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-sky-500" placeholder="Your Name" required>
                            </div>
                            <div>
                                <label for="phone" class="sr-only">Phone</label>
                                <input type="tel" name="phone" id="phone" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-sky-500" placeholder="Your Phone Number" required>
                            </div>
                             <div>
                                <label for="service" class="sr-only">Service Needed</label>
                                <input type="text" name="service" id="service" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-sky-500" placeholder="What service do you need? (e.g., Leak Repair)">
                            </div>
                            <div>
                                <label for="address" class="sr-only">Address</label>
                                <textarea name="address" id="address" rows="3" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-sky-500" placeholder="Your Address"></textarea>
                            </div>
                            <button type="submit" class="w-full bg-orange-500 text-white font-bold py-3 px-6 rounded-lg hover:bg-orange-600 transition duration-300">
                                Send Service Request
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <footer class="bg-gray-800 text-white">
        <div class="container mx-auto px-6 py-8">
            <div class="md:flex md:justify-between">
                <div class="mb-6 md:mb-0">
                    <h3 class="text-2xl font-bold text-white">UrbanSmart Plumbing</h3>
                    <p class="text-gray-400">Led by Krishna Yadav</p>
                    <p class="text-gray-400">Balaghat, Madhya Pradesh</p>
                </div>
                <div class="flex space-x-8">
                    <div>
                        <h4 class="font-semibold mb-2">Quick Links</h4>
                        <ul>
                            <li><a href="#services" class="text-gray-400 hover:text-white">Services</a></li>
                            <li><a href="#rates" class="text-gray-400 hover:text-white">Rate List</a></li>
                            <li><a href="#contact" class="text-gray-400 hover:text-white">Contact</a></li>
                        </ul>
                    </div>
                    <div>
                        <h4 class="font-semibold mb-2">Contact Us</h4>
                        <ul>
                            <li class="text-gray-400">+91-74890 77309</li>
                        </ul>
                    </div>
                </div>
            </div>
            <hr class="my-6 border-gray-600">
            <div class="sm:flex sm:justify-between sm:items-center text-center">
                <p class="text-gray-400 text-sm mb-4 sm:mb-0">
                    &copy; 2025 UrbanSmart Plumbing. All Rights Reserved.
                </p>
                <div class="flex justify-center space-x-6">
                    <a href="#" aria-label="Facebook" class="text-gray-400 hover:text-white transition duration-300">
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path fill-rule="evenodd" d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z" clip-rule="evenodd" /></svg>
                    </a>
                    <a href="#" aria-label="Instagram" class="text-gray-400 hover:text-white transition duration-300">
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path fill-rule="evenodd" d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.398 1.363.465 2.427.048 1.024.06 1.378.06 3.808s-.012 2.784-.06 3.808c-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.398-2.427.465-1.024.048-1.378.06-3.808.06s-2.784-.012-3.808-.06c-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.398-1.363-.465-2.427-.048-1.024-.06-1.378-.06-3.808s.012-2.784.06-3.808c.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 016.08 2.525c.636-.247 1.363-.398 2.427-.465C9.53 2.013 9.884 2 12.315 2zM12 7a5 5 0 100 10 5 5 0 000-10zm0-2a7 7 0 110 14 7 7 0 010-14zm4.5-1.5a1.5 1.5 0 100-3 1.5 1.5 0 000 3z" clip-rule="evenodd" /></svg>
                    </a>
                    <a href="#" aria-label="YouTube" class="text-gray-400 hover:text-white transition duration-300">
                        <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true"><path fill-rule="evenodd" d="M19.812 5.418c.861.23 1.538.907 1.768 1.768C21.998 8.78 22 12 22 12s0 3.22-.42 4.814c-.23.861-.907 1.538-1.768 1.768C18.219 19 12 19 12 19s-6.219 0-7.812-.42c-.861-.23-1.538-.907-1.768-1.768C2.002 15.22 2 12 2 12s0-3.22.42-4.814c.23-.861.907-1.538 1.768-1.768C5.781 5 12 5 12 5s6.219 0 7.812.418zM9.57 15.584l6.166-3.583-6.166-3.584v7.167z" clip-rule="evenodd" /></svg>
                    </a>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // JavaScript for mobile menu toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // JavaScript for tabs in the rate list section
        function openTab(event, tabName) {
            // Hide all tab content
            let tabcontent = document.getElementsByClassName("tab-content");
            for (let i = 0; i < tabcontent.length; i++) {
                tabcontent[i].style.display = "none";
            }

            // Deactivate all tab buttons
            let tabbuttons = document.getElementsByClassName("tab-button");
            for (let i = 0; i < tabbuttons.length; i++) {
                tabbuttons[i].classList.remove("tab-active");
                tabbuttons[i].classList.add("tab-inactive");
            }

            // Show the current tab and activate its button
            document.getElementById(tabName).style.display = "block";
            event.currentTarget.classList.add("tab-active");
            event.currentTarget.classList.remove("tab-inactive");
        }
    </script>

</body>
</html>
```
