<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Muhammad Farhan Tanvir | Data Scientist Profile</title>
    <!-- Load Tailwind CSS --><script src="https://cdn.tailwindcss.com"></script>
    <!-- Load Inter Font --><link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap" rel="stylesheet">
    
    <style>
        /* --- CUSTOM ANIMATIONS (Reduced to only the skill card pulse) --- */
        /* Keyframes for the Skill Card Subtle Pulse Effect (Purple Glow on Light BG) */
        @keyframes subtle-pulse {
            0%, 100% {
                box-shadow: 0 0 5px rgba(126, 34, 206, 0.2), 0 0 0px rgba(126, 34, 206, 0);
            }
            50% {
                box-shadow: 0 0 10px rgba(126, 34, 206, 0.5), 0 0 10px rgba(126, 34, 206, 0.1);
            }
        }

        /* --- STYLING --- */
        /* Apply the animation to skill cards */
        .skill-card {
            transition: all 0.3s ease;
            animation: subtle-pulse 4s infinite ease-in-out;
        }
        .skill-card:hover {
            transform: translateY(-5px) scale(1.03);
            /* Darker shadow on hover for white background */
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1), 0 0 30px rgba(126, 34, 206, 0.4);
        }
        
        /* Root styling for a clean, light look */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #ffffff; /* White background */
            color: #333333; /* Dark text */
        }
        .section-header {
            border-left: 4px solid #7e22ce; /* Deep Purple accent */
            padding-left: 1rem;
            color: #1a202c; /* Dark header text */
        }
        
        /* Generic class replacements for the light theme */
        .card-bg {
            background-color: #f7f7f7;
            border: 1px solid #e0e0e0;
        }
        .card-bg:hover {
            background-color: #eeeeee;
        }
        .view-card {
             /* Light purple border for focus */
            border: 2px solid #a855f7;
            background-color: #f3e8ff; /* Very light purple background */
        }
    </style>
</head>
<body class="p-4 md:p-8 lg:p-12">

    <div class="max-w-6xl mx-auto">

        <!-- HEADER & CONTACT SECTION -->
        <header class="text-center mb-12 py-8 border-b border-gray-200">
            <h1 class="text-5xl md:text-6xl font-extrabold text-gray-900 mb-2 tracking-tighter">
                Muhammad Farhan Tanvir
            </h1>
            
            <!-- Static Text Section -->
            <h2 class="text-2xl font-light text-gray-700 mb-6">
                <span class="font-semibold text-gray-900">Data Scientist</span> | Specialized in <span class="font-bold text-purple-600">NLP, AI Agent, RAG and LLMs</span>
            </h2>

            <!-- Contact Links -->
            <div class="flex flex-wrap justify-center space-x-4 md:space-x-6">
                <!-- Links (Using original badge format for dynamic loading) -->
                <a href="https://www.linkedin.com/in/muhammad-farhan-tanvir" target="_blank" class="transform hover:scale-105 transition duration-300">
                    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
                </a>
                <a href="https://farhan-ai-insights.lovable.app" target="_blank" class="transform hover:scale-105 transition duration-300">
                    <img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white" alt="Portfolio">
                </a>
                <a href="mailto:tanvirf07@gmail.com" class="transform hover:scale-105 transition duration-300">
                    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
                </a>
            </div>
        </header>

        <!-- ABOUT ME / PHILOSOPHY -->
        <section class="mb-12 p-6 card-bg rounded-xl shadow-lg border border-gray-200">
            <blockquote class="italic text-lg md:text-xl text-center text-purple-600 font-light">
                "Transforming complex data into actionable insights through cutting-edge AI and machine learning solutions"
            </blockquote>
            <p class="mt-4 text-gray-700 text-center">
                <span class="font-medium text-gray-900">Data Scientist</span> with 3+ years of experience in NLP, LLMs, and AI-driven analytics. Master's student at Universität Potsdam, currently based in Dortmund, Germany. Passionate about building <span class="text-purple-600">interpretable, ethical, and human-centered</span> AI systems.
            </p>
        </section>

        <!-- ANIMATED TECH STACK & EXPERTISE -->
        <div class="mb-12">
            <h3 class="section-header text-3xl font-bold mb-8 text-gray-900">
                Tech Stack & Core Expertise
            </h3>

            <!-- Grid of Animated Skills -->
            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-6">
                
                <!-- Programming Languages -->
                <div class="skill-card bg-white p-4 rounded-xl flex flex-col items-center justify-center text-center border border-purple-300 hover:bg-gray-100 shadow-md">
                    <span class="text-4xl mb-1 text-yellow-500">🐍</span>
                    <p class="font-bold text-gray-900">Python</p>
                    <small class="text-purple-600">ML / Data</small>
                </div>
                <div class="skill-card bg-white p-4 rounded-xl flex flex-col items-center justify-center text-center border border-purple-300 hover:bg-gray-100 shadow-md">
                    <span class="text-4xl mb-1 text-blue-500">®</span>
                    <p class="font-bold text-gray-900">R</p>
                    <small class="text-purple-600">Statistical Modeling</small>
                </div>

                <!-- AI/ML Frameworks -->
                <div class="skill-card bg-white p-4 rounded-xl flex flex-col items-center justify-center text-center border border-purple-300 hover:bg-gray-100 shadow-md">
                    <span class="text-4xl mb-1 text-red-600">🧠</span>
                    <p class="font-bold text-gray-900">TensorFlow/Keras</p>
                    <small class="text-purple-600">Deep Learning</small>
                </div>
                <div class="skill-card bg-white p-4 rounded-xl flex flex-col items-center justify-center text-center border border-purple-300 hover:bg-gray-100 shadow-md">
                    <span class="text-4xl mb-1 text-orange-600">⚡</span>
                    <p class="font-bold text-gray-900">PyTorch</p>
                    <small class="text-purple-600">Research & LLMs</small>
                </div>
                <div class="skill-card bg-white p-4 rounded-xl flex flex-col items-center justify-center text-center border border-purple-300 hover:bg-gray-100 shadow-md">
                    <span class="text-4xl mb-1 text-cyan-500">🧪</span>
                    <p class="font-bold text-gray-900">Scikit-Learn</p>
                    <small class="text-purple-600">Classic ML</small>
                </div>

                <!-- Data/LLM Ecosystem -->
                <div class="skill-card bg-white p-4 rounded-xl flex flex-col items-center justify-center text-center border border-purple-300 hover:bg-gray-100 shadow-md">
                    <span class="text-4xl mb-1 text-green-500">💬</span>
                    <p class="font-bold text-gray-900">LangChain</p>
                    <small class="text-purple-600">RAG / Agents</small>
                </div>
                <div class="skill-card bg-white p-4 rounded-xl flex flex-col items-center justify-center text-center border border-purple-300 hover:bg-gray-100 shadow-md">
                    <span class="text-4xl mb-1 text-gray-700">💾</span>
                    <p class="font-bold text-gray-900">SQL/BigQuery</p>
                    <small class="text-purple-600">Data Warehousing</small>
                </div>
                <div class="skill-card bg-white p-4 rounded-xl flex flex-col items-center justify-center text-center border border-purple-300 hover:bg-gray-100 shadow-md">
                    <span class="text-4xl mb-1 text-amber-600">📈</span>
                    <p class="font-bold text-gray-900">Pandas/NumPy</p>
                    <small class="text-purple-600">Data Prep</small>
                </div>

                <!-- Cloud & MLOps -->
                <div class="skill-card bg-white p-4 rounded-xl flex flex-col items-center justify-center text-center border border-purple-300 hover:bg-gray-100 shadow-md">
                    <span class="text-4xl mb-1 text-blue-600">☁️</span>
                    <p class="font-bold text-gray-900">GCP/AWS/Azure</p>
                    <small class="text-purple-600">Deployment</small>
                </div>
                <div class="skill-card bg-white p-4 rounded-xl flex flex-col items-center justify-center text-center border border-purple-300 hover:bg-gray-100 shadow-md">
                    <span class="text-4xl mb-1 text-sky-500">🐳</span>
                    <p class="font-bold text-gray-900">Docker</p>
                    <small class="text-purple-600">Containerization</small>
                </div>
                <div class="skill-card bg-white p-4 rounded-xl flex flex-col items-center justify-center text-center border border-purple-300 hover:bg-gray-100 shadow-md">
                    <span class="text-4xl mb-1 text-teal-500">🎨</span>
                    <p class="font-bold text-gray-900">Tableau/PowerBI</p>
                    <small class="text-purple-600">Data Viz</small>
                </div>
                 <div class="skill-card bg-white p-4 rounded-xl flex flex-col items-center justify-center text-center border border-purple-300 hover:bg-gray-100 shadow-md">
                    <span class="text-4xl mb-1 text-red-500">⚙️</span>
                    <p class="font-bold text-gray-900">MLOps</p>
                    <small class="text-purple-600">Pipelines</small>
                </div>
            </div>
        </div>

        <!-- PROFESSIONAL EXPERIENCE -->
        <div class="mb-12">
            <h3 class="section-header text-3xl font-bold mb-8 text-gray-900">
                Professional & Research Experience
            </h3>

            <!-- Current Role -->
            <div class="p-6 card-bg rounded-xl shadow-lg mb-4 border border-gray-200">
                <p class="text-lg font-semibold text-gray-900">Data Scientist</p>
                <p class="text-purple-600">Institut für Marktforschung, Statistik und Prognose (IMSP) | Munich, Germany</p>
                <p class="text-sm text-gray-500 mb-3">Apr 2023 – Sep 2025</p>
                <ul class="list-disc list-inside space-y-1 text-gray-700 ml-4">
                    <li>🚀 Deployed sales forecasting models on Google Cloud Platform using BigQuery, ensuring operational scalability.</li>
                    <li>📈 Improved data quality by 20% through automated cleaning pipelines, enhancing model reliability.</li>
                </ul>
            </div>

            <!-- Research Experience -->
             <div class="p-6 card-bg rounded-xl shadow-lg border border-gray-200">
                <p class="text-lg font-semibold text-gray-900">Research Assistant</p>
                <p class="text-purple-600">Technische Universität Dortmund | May 2024 – Oct 2024</p>
                <ul class="list-disc list-inside space-y-1 text-gray-700 ml-4">
                    <li>Developed interactive warehouse planning modeling environments for complex logistical analysis.</li>
                    <li>Supported evidence-based decision-making through comprehensive data analysis.</li>
                </ul>
            </div>
        </div>

        <!-- FEATURED PROJECTS -->
        <div class="mb-12">
            <h3 class="section-header text-3xl font-bold mb-8 text-gray-900">
                Featured Data Science Projects
            </h3>
            
            <div class="grid md:grid-cols-2 gap-6">
                <!-- Project 1 -->
                <div class="p-6 card-bg rounded-xl shadow-lg border-t-4 border-purple-500 hover:bg-gray-100 transition duration-300">
                    <h4 class="text-xl font-bold text-gray-900 mb-2">🤖 Coding Documentation Generator (LLMs)</h4>
                    <p class="text-sm text-purple-600 mb-3">Stack: Streamlit, Ollama, LangChain, DeepSeek LLMs</p>
                    <ul class="list-disc list-inside text-gray-700 ml-4 space-y-1">
                        <li>Automated code documentation using DeepSeek R1-1.5B/Coder-6.7B for efficiency.</li>
                        <li>Built robust LangChain pipelines for dynamic docstring generation across repositories.</li>
                    </ul>
                </div>
                <!-- Project 2 -->
                <div class="p-6 card-bg rounded-xl shadow-lg border-t-4 border-teal-500 hover:bg-gray-100 transition duration-300">
                    <h4 class="text-xl font-bold text-gray-900 mb-2">🎯 Advanced Uncertainty Quantification</h4>
                    <p class="text-sm text-purple-600 mb-3">Stack: PyTorch, FastAI, Neptune AI, Plotly</p>
                    <ul class="list-disc list-inside text-gray-700 ml-4 space-y-1">
                        <li>Customized ConvNeXt model for CIFAR-10 classification with advanced metrics.</li>
                        <li>Implemented aleatoric & epistemic uncertainty analysis to enhance model reliability.</li>
                    </ul>
                </div>
                <!-- Project 3 -->
                <div class="p-6 card-bg rounded-xl shadow-lg border-t-4 border-amber-500 hover:bg-gray-100 transition duration-300">
                    <h4 class="text-xl font-bold text-gray-900 mb-2">👁️ Real-Time Object Detection (YOLOv6)</h4>
                    <p class="text-sm text-purple-600 mb-3">Stack: OpenCV, YOLOv6, NumPy</p>
                    <ul class="list-disc list-inside text-gray-700 ml-4 space-y-1">
                        <li>Fine-tuned YOLOv6 for custom object detection, optimizing detection performance.</li>
                        <li>Achieved high accuracy using mAP, precision, recall metrics on real-world data.</li>
                    </ul>
                </div>
                <!-- Project 4 -->
                <div class="p-6 card-bg rounded-xl shadow-lg border-t-4 border-pink-500 hover:bg-gray-100 transition duration-300">
                    <h4 class="text-xl font-bold text-gray-900 mb-2">📊 Sales Performance Dashboard</h4>
                    <p class="text-sm text-purple-600 mb-3">Stack: Power BI, Data Visualization, SQL</p>
                    <ul class="list-disc list-inside text-gray-700 ml-4 space-y-1">
                        <li>Created comprehensive sales analytics dashboard visualized key performance indicators.</li>
                        <li>Enabled data-driven shipping optimization strategies leading to cost reduction.</li>
                    </ul>
                </div>
            </div>
        </div>

        <!-- GITHUB ANALYTICS & EDUCATION -->
        <div class="grid md:grid-cols-2 gap-8 mb-12">
            <!-- Analytics -->
            <div>
                <h3 class="section-header text-3xl font-bold mb-8 text-gray-900">
                    Profile Analytics (Live)
                </h3>
                <div class="space-y-4">
                    
                    <!-- CUSTOM TOP LANGUAGES CARD (98% Python, 2% R) -->
                    <div class="p-4 card-bg rounded-xl shadow-lg border border-gray-200">
                        <h4 class="text-xl font-bold text-gray-900 mb-4 text-center">Top Language Distribution</h4>
                        <div class="space-y-3">
                            <!-- Python 98% -->
                            <div>
                                <div class="flex justify-between text-sm font-medium text-gray-700">
                                    <span class="flex items-center">
                                        <span class="w-3 h-3 bg-yellow-500 rounded-full mr-2"></span> Python
                                    </span>
                                    <span>98%</span>
                                </div>
                                <div class="w-full bg-gray-300 rounded-full h-2.5">
                                    <div class="bg-yellow-500 h-2.5 rounded-full" style="width: 98%;"></div>
                                </div>
                            </div>
                            <!-- R 2% -->
                            <div>
                                <div class="flex justify-between text-sm font-medium text-gray-700">
                                    <span class="flex items-center">
                                        <span class="w-3 h-3 bg-blue-500 rounded-full mr-2"></span> R
                                    </span>
                                    <span>2%</span>
                                </div>
                                <div class="w-full bg-gray-300 rounded-full h-2.5">
                                    <div class="bg-blue-500 h-2.5 rounded-full" style="width: 2%;"></div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Profile Views per period (Now Live) -->
                    <div class="grid grid-cols-1 sm:grid-cols-3 gap-4">
                        <div class="p-4 view-card rounded-xl shadow-lg flex flex-col items-center">
                            <h4 class="text-md font-semibold text-gray-800 mb-2">Views per Day</h4>
                            <!-- Placeholder for Live Data -->
                            <div id="views-day" class="text-3xl font-bold text-purple-800">0</div>
                            <span class="text-purple-600 text-sm">📈 Live Count</span>
                        </div>
                        <div class="p-4 view-card rounded-xl shadow-lg flex flex-col items-center">
                            <h4 class="text-md font-semibold text-gray-800 mb-2">Views per Week</h4>
                            <!-- Placeholder for Live Data -->
                            <div id="views-week" class="text-3xl font-bold text-purple-800">0</div>
                            <span class="text-purple-600 text-sm">📊 Live Count</span>
                        </div>
                        <div class="p-4 view-card rounded-xl shadow-lg flex flex-col items-center">
                            <h4 class="text-md font-semibold text-gray-800 mb-2">Views per Month</h4>
                            <!-- Placeholder for Live Data -->
                            <div id="views-month" class="text-3xl font-bold text-purple-800">0</div>
                            <span class="text-purple-600 text-sm">🗓️ Live Count</span>
                        </div>
                    </div>
                    <!-- Note for the user about the live data -->
                    <p class="text-xs text-center text-gray-500 italic mt-2">
                        *Profile views are tracked and incremented live using the Firestore database. Counts reset automatically based on server time for Day, Week (Monday start), and Month.
                    </p>
                </div>
            </div>
            
            <!-- Education -->
            <div>
                <h3 class="section-header text-3xl font-bold mb-8 text-gray-900">
                    Education & Languages
                </h3>
                <div class="p-6 card-bg rounded-xl shadow-lg border border-gray-200 mb-6">
                    <p class="text-lg font-semibold text-gray-900">Master of Science in Data Science</p>
                    <p class="text-purple-600">Universität Potsdam | 2022 – Present</p>
                </div>
                <div class="p-6 card-bg rounded-xl shadow-lg border border-gray-200">
                    <p class="text-lg font-semibold text-gray-900 mb-3">Language Proficiency</p>
                    <ul class="text-gray-700 space-y-2">
                        <li><span class="font-medium text-gray-900">Bengali:</span> Native Speaker</li>
                        <li><span class="font-medium text-gray-900">English:</span> C1 (Advanced)</li>
                        <li><span class="font-medium text-gray-900">German:</span> B1 (Intermediate)</li>
                    </ul>
                </div>
            </div>
        </div>


        <!-- FOOTER / CALL TO ACTION -->
        <footer class="text-center py-8 border-t border-gray-200 mt-12">
            <h4 class="text-2xl font-semibold text-purple-600 mb-3">
                🤝 Let's Collaborate!
            </h4>
            <p class="text-gray-700 mb-6 max-w-2xl mx-auto">
                I'm always excited to discuss innovative data science projects, from NLP research to scalable deep learning applications. Feel free to connect via the links above!
            </p>
            <div class="text-lg font-light text-gray-500">
                <span class="text-purple-600">*"Turning data into decisions"*</span> 🚀
            </div>
        </footer>

    </div>
    
    <!-- Firebase Initialization and View Tracking Script -->
    <script type="module">
        import { initializeApp } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-app.js";
        import { getAuth, signInAnonymously, signInWithCustomToken } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-auth.js";
        import { getFirestore, doc, onSnapshot, setDoc, increment, serverTimestamp } from "https://www.gstatic.com/firebasejs/11.6.1/firebase-firestore.js";
        
        // Use global variables provided by the environment
        const appId = typeof __app_id !== 'undefined' ? __app_id : 'default-app-id';
        const firebaseConfig = JSON.parse(typeof __firebase_config !== 'undefined' ? __firebase_config : '{}');
        const initialAuthToken = typeof __initial_auth_token !== 'undefined' ? __initial_auth_token : null;

        let db, auth;
        const VIEW_DOC_PATH = `/artifacts/${appId}/public/data/profile_views/main_tracker`;

        // Utility function to determine if a period needs resetting
        function needsReset(lastResetTimestamp, unit) {
            if (!lastResetTimestamp) return true;

            const now = new Date();
            const lastReset = lastResetTimestamp.toDate ? lastResetTimestamp.toDate() : new Date(lastResetTimestamp);
            
            switch (unit) {
                case 'day':
                    return now.toDateString() !== lastReset.toDateString();
                case 'week':
                    // Monday is day 1, Sunday is day 0. We want Monday as the start of the week.
                    const startOfWeekNow = new Date(now);
                    const dayNow = (now.getDay() + 6) % 7; // Monday=0, Sunday=6
                    startOfWeekNow.setDate(now.getDate() - dayNow);
                    startOfWeekNow.setHours(0, 0, 0, 0);

                    const startOfWeekLastReset = new Date(lastReset);
                    const dayLastReset = (lastReset.getDay() + 6) % 7;
                    startOfWeekLastReset.setDate(lastReset.getDate() - dayLastReset);
                    startOfWeekLastReset.setHours(0, 0, 0, 0);

                    return startOfWeekNow.getTime() !== startOfWeekLastReset.getTime();
                case 'month':
                    return now.getMonth() !== lastReset.getMonth() || now.getFullYear() !== lastReset.getFullYear();
                default:
                    return false;
            }
        }

        async function initFirebase() {
            try {
                const app = initializeApp(firebaseConfig);
                db = getFirestore(app);
                auth = getAuth(app);
                
                // 1. Authenticate
                if (initialAuthToken) {
                    await signInWithCustomToken(auth, initialAuthToken);
                } else {
                    await signInAnonymously(auth);
                }
                
                // 2. Start tracking and listening after auth
                trackView();
                setupRealtimeListener();

            } catch (error) {
                console.error("Firebase initialization or authentication failed:", error);
            }
        }
        
        async function trackView() {
            if (!db) return; // Guard clause if DB didn't initialize

            const viewRef = doc(db, VIEW_DOC_PATH);

            try {
                // Get the current document state
                const {
                    dailyViews, dailyLastReset, 
                    weeklyViews, weeklyLastReset, 
                    monthlyViews, monthlyLastReset
                } = await new Promise(resolve => {
                    const unsubscribe = onSnapshot(viewRef, (docSnap) => {
                        unsubscribe(); // Unsubscribe immediately after getting the initial data
                        resolve(docSnap.data() || {});
                    }, (error) => {
                        console.error("Error reading initial view data:", error);
                        resolve({});
                    });
                });
                
                // Prepare update object with increments
                const updateData = {
                    dailyViews: increment(1),
                    weeklyViews: increment(1),
                    monthlyViews: increment(1),
                    lastViewed: serverTimestamp() // Always update the last viewed time
                };

                // Check and apply resets if necessary
                if (needsReset(dailyLastReset, 'day')) {
                    updateData.dailyViews = 1;
                    updateData.dailyLastReset = serverTimestamp();
                }
                if (needsReset(weeklyLastReset, 'week')) {
                    updateData.weeklyViews = 1;
                    updateData.weeklyLastReset = serverTimestamp();
                }
                if (needsReset(monthlyLastReset, 'month')) {
                    updateData.monthlyViews = 1;
                    updateData.monthlyLastReset = serverTimestamp();
                }
                
                // Try to update, or create if it doesn't exist
                await setDoc(viewRef, updateData, { merge: true });

            } catch (error) {
                console.error("Error updating view count:", error);
            }
        }

        function setupRealtimeListener() {
            if (!db) return;

            const viewRef = doc(db, VIEW_DOC_PATH);
            
            onSnapshot(viewRef, (docSnap) => {
                const data = docSnap.data();
                
                // Get current values (or 0 if not present)
                const currentDaily = data?.dailyViews || 0;
                const currentWeekly = data?.weeklyViews || 0;
                const currentMonthly = data?.monthlyViews || 0;

                // Update the DOM elements
                const viewsDayEl = document.getElementById('views-day');
                const viewsWeekEl = document.getElementById('views-week');
                const viewsMonthEl = document.getElementById('views-month');

                if (viewsDayEl) viewsDayEl.textContent = currentDaily;
                if (viewsWeekEl) viewsWeekEl.textContent = currentWeekly;
                if (viewsMonthEl) viewsMonthEl.textContent = currentMonthly;

            }, (error) => {
                console.error("Error listening to view changes:", error);
                // Fallback to displaying 0 on error
                document.getElementById('views-day').textContent = 'Error';
                document.getElementById('views-week').textContent = 'Error';
                document.getElementById('views-month').textContent = 'Error';
            });
        }

        window.onload = initFirebase;
    </script>

</body>
</html>