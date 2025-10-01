<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README - Web Writer</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            box-sizing: border-box;
        }
        
        .code-block {
            background: #1f2937;
            color: #f9fafb;
            border-radius: 8px;
            padding: 1rem;
            font-family: 'Courier New', monospace;
            overflow-x: auto;
        }
        
        .feature-card {
            transition: transform 0.2s ease;
        }
        
        .feature-card:hover {
            transform: translateY(-2px);
        }
        
        .section {
            scroll-margin-top: 2rem;
        }
    </style>
</head>
<body class="bg-gradient-to-br from-slate-50 to-blue-50 min-h-screen font-sans">
    <div class="container mx-auto px-4 py-8 max-w-4xl">
        <!-- Header -->
        <div class="text-center mb-12">
            <h1 class="text-5xl font-bold text-gray-800 mb-4">📝 Web Writer</h1>
            <p class="text-xl text-gray-600 mb-6">A Beautiful, Distraction-Free Writing Experience</p>
            <div class="flex justify-center gap-4 flex-wrap">
                <span class="bg-blue-100 text-blue-800 px-3 py-1 rounded-full text-sm font-medium">HTML5</span>
                <span class="bg-green-100 text-green-800 px-3 py-1 rounded-full text-sm font-medium">JavaScript</span>
                <span class="bg-purple-100 text-purple-800 px-3 py-1 rounded-full text-sm font-medium">Tailwind CSS</span>
                <span class="bg-orange-100 text-orange-800 px-3 py-1 rounded-full text-sm font-medium">Responsive</span>
            </div>
        </div>

        <!-- Table of Contents -->
        <div class="bg-white rounded-lg shadow-lg p-6 mb-8">
            <h2 class="text-2xl font-bold text-gray-800 mb-4">📋 Table of Contents</h2>
            <nav class="grid grid-cols-1 md:grid-cols-2 gap-2">
                <a href="#overview" class="text-blue-600 hover:text-blue-800 hover:underline">🎯 Overview</a>
                <a href="#features" class="text-blue-600 hover:text-blue-800 hover:underline">✨ Features</a>
                <a href="#installation" class="text-blue-600 hover:text-blue-800 hover:underline">🚀 Installation</a>
                <a href="#usage" class="text-blue-600 hover:text-blue-800 hover:underline">📖 Usage Guide</a>
                <a href="#technical" class="text-blue-600 hover:text-blue-800 hover:underline">⚙️ Technical Details</a>
                <a href="#customization" class="text-blue-600 hover:text-blue-800 hover:underline">🎨 Customization</a>
                <a href="#browser-support" class="text-blue-600 hover:text-blue-800 hover:underline">🌐 Browser Support</a>
                <a href="#contributing" class="text-blue-600 hover:text-blue-800 hover:underline">🤝 Contributing</a>
            </nav>
        </div>

        <!-- Overview -->
        <section id="overview" class="section bg-white rounded-lg shadow-lg p-8 mb-8">
            <h2 class="text-3xl font-bold text-gray-800 mb-6">🎯 Overview</h2>
            <p class="text-gray-700 text-lg leading-relaxed mb-4">
                Web Writer is a modern, distraction-free writing application built entirely with vanilla HTML, CSS, and JavaScript. 
                It provides a clean, professional interface for writers, bloggers, students, and anyone who needs a focused writing environment.
            </p>
            <p class="text-gray-700 text-lg leading-relaxed">
                The application runs entirely in the browser with no server dependencies, making it perfect for offline use and easy deployment.
            </p>
        </section>

        <!-- Features -->
        <section id="features" class="section bg-white rounded-lg shadow-lg p-8 mb-8">
            <h2 class="text-3xl font-bold text-gray-800 mb-6">✨ Features</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <div class="feature-card bg-blue-50 p-4 rounded-lg">
                    <h3 class="font-semibold text-blue-800 mb-2">📝 Rich Text Editing</h3>
                    <p class="text-gray-700 text-sm">Bold, italic, underline formatting with keyboard shortcuts</p>
                </div>
                <div class="feature-card bg-green-50 p-4 rounded-lg">
                    <h3 class="font-semibold text-green-800 mb-2">📊 Real-time Statistics</h3>
                    <p class="text-gray-700 text-sm">Word count, character count, reading time, and more</p>
                </div>
                <div class="feature-card bg-purple-50 p-4 rounded-lg">
                    <h3 class="font-semibold text-purple-800 mb-2">💾 Auto-save</h3>
                    <p class="text-gray-700 text-sm">Automatic saving to browser storage every 2 seconds</p>
                </div>
                <div class="feature-card bg-orange-50 p-4 rounded-lg">
                    <h3 class="font-semibold text-orange-800 mb-2">📤 Export Options</h3>
                    <p class="text-gray-700 text-sm">Download documents as text files</p>
                </div>
                <div class="feature-card bg-pink-50 p-4 rounded-lg">
                    <h3 class="font-semibold text-pink-800 mb-2">📱 Responsive Design</h3>
                    <p class="text-gray-700 text-sm">Works perfectly on desktop, tablet, and mobile</p>
                </div>
                <div class="feature-card bg-indigo-50 p-4 rounded-lg">
                    <h3 class="font-semibold text-indigo-800 mb-2">🎨 Beautiful UI</h3>
                    <p class="text-gray-700 text-sm">Clean, modern interface with smooth animations</p>
                </div>
            </div>
        </section>

        <!-- Installation -->
        <section id="installation" class="section bg-white rounded-lg shadow-lg p-8 mb-8">
            <h2 class="text-3xl font-bold text-gray-800 mb-6">🚀 Installation</h2>
            <div class="space-y-6">
                <div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Option 1: Direct Download</h3>
                    <ol class="list-decimal list-inside space-y-2 text-gray-700">
                        <li>Download the HTML file</li>
                        <li>Open it in any modern web browser</li>
                        <li>Start writing immediately!</li>
                    </ol>
                </div>
                
                <div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Option 2: Web Server</h3>
                    <p class="text-gray-700 mb-3">For enhanced functionality, serve the file through a web server:</p>
                    <div class="code-block">
# Using Python 3
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server

# Using PHP
php -S localhost:8000
                    </div>
                </div>
            </div>
        </section>

        <!-- Usage Guide -->
        <section id="usage" class="section bg-white rounded-lg shadow-lg p-8 mb-8">
            <h2 class="text-3xl font-bold text-gray-800 mb-6">📖 Usage Guide</h2>
            <div class="space-y-6">
                <div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Getting Started</h3>
                    <ol class="list-decimal list-inside space-y-2 text-gray-700">
                        <li>Click on "Document Title" to add a title to your document</li>
                        <li>Click in the main writing area to start typing</li>
                        <li>Use the toolbar buttons for formatting</li>
                        <li>Watch your writing statistics update in real-time</li>
                    </ol>
                </div>
                
                <div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Keyboard Shortcuts</h3>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                        <div class="bg-gray-50 p-3 rounded">
                            <strong>Ctrl/Cmd + B:</strong> Bold text
                        </div>
                        <div class="bg-gray-50 p-3 rounded">
                            <strong>Ctrl/Cmd + I:</strong> Italic text
                        </div>
                        <div class="bg-gray-50 p-3 rounded">
                            <strong>Ctrl/Cmd + U:</strong> Underline text
                        </div>
                        <div class="bg-gray-50 p-3 rounded">
                            <strong>Ctrl/Cmd + S:</strong> Save document
                        </div>
                    </div>
                </div>
                
                <div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Saving & Exporting</h3>
                    <ul class="list-disc list-inside space-y-2 text-gray-700">
                        <li><strong>Auto-save:</strong> Documents are automatically saved to your browser's local storage</li>
                        <li><strong>Manual save:</strong> Click the "Save" button or use Ctrl/Cmd + S</li>
                        <li><strong>Export:</strong> Click "Export" to download your document as a text file</li>
                        <li><strong>New document:</strong> Click "New Document" to start fresh</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Technical Details -->
        <section id="technical" class="section bg-white rounded-lg shadow-lg p-8 mb-8">
            <h2 class="text-3xl font-bold text-gray-800 mb-6">⚙️ Technical Details</h2>
            <div class="space-y-6">
                <div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Technologies Used</h3>
                    <ul class="list-disc list-inside space-y-2 text-gray-700">
                        <li><strong>HTML5:</strong> Semantic markup and contenteditable API</li>
                        <li><strong>CSS3:</strong> Modern styling with Flexbox and Grid</li>
                        <li><strong>JavaScript (ES6+):</strong> Vanilla JS for all functionality</li>
                        <li><strong>Tailwind CSS:</strong> Utility-first CSS framework via CDN</li>
                        <li><strong>Local Storage API:</strong> Browser-based document persistence</li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">File Structure</h3>
                    <div class="code-block">
web-writer/
├── index.html          # Main application file
├── README.md          # This documentation
└── assets/            # Optional: custom assets
    ├── icons/         # Custom icons (if any)
    └── fonts/         # Custom fonts (if any)
                    </div>
                </div>
                
                <div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Key Functions</h3>
                    <ul class="list-disc list-inside space-y-2 text-gray-700">
                        <li><code class="bg-gray-100 px-2 py-1 rounded">updateCounts()</code> - Updates word count and statistics</li>
                        <li><code class="bg-gray-100 px-2 py-1 rounded">formatText()</code> - Applies text formatting</li>
                        <li><code class="bg-gray-100 px-2 py-1 rounded">saveDocument()</code> - Saves to local storage</li>
                        <li><code class="bg-gray-100 px-2 py-1 rounded">exportDocument()</code> - Downloads as text file</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Customization -->
        <section id="customization" class="section bg-white rounded-lg shadow-lg p-8 mb-8">
            <h2 class="text-3xl font-bold text-gray-800 mb-6">🎨 Customization</h2>
            <div class="space-y-6">
                <div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Changing Colors</h3>
                    <p class="text-gray-700 mb-3">Modify the Tailwind classes to change the color scheme:</p>
                    <div class="code-block">
/* Change primary color from blue to green */
bg-blue-600 → bg-green-600
text-blue-600 → text-green-600
hover:bg-blue-700 → hover:bg-green-700
                    </div>
                </div>
                
                <div>
                    <h3 class="text-xl font-semibold text-gray-800 mb-3">Adding Features</h3>
                    <ul class="list-disc list-inside space-y-2 text-gray-700">
                        <li>Add new toolbar buttons by extending the toolbar section</li>
                        <li>Implement additional statistics in the <code class="bg-gray-100 px-2 py-1 rounded">updateCounts()</code> function</li>
                        <li>Add export formats (PDF, HTML) by modifying <code class="bg-gray-100 px-2 py-1 rounded">exportDocument()</code></li>
                        <li>Integrate with cloud storage APIs for online saving</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Browser Support -->
        <section id="browser-support" class="section bg-white rounded-lg shadow-lg p-8 mb-8">
            <h2 class="text-3xl font-bold text-gray-800 mb-6">🌐 Browser Support</h2>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
                <div class="text-center p-4 bg-green-50 rounded-lg">
                    <div class="text-2xl mb-2">✅</div>
                    <div class="font-semibold">Chrome 60+</div>
                </div>
                <div class="text-center p-4 bg-green-50 rounded-lg">
                    <div class="text-2xl mb-2">✅</div>
                    <div class="font-semibold">Firefox 55+</div>
                </div>
                <div class="text-center p-4 bg-green-50 rounded-lg">
                    <div class="text-2xl mb-2">✅</div>
                    <div class="font-semibold">Safari 12+</div>
                </div>
                <div class="text-center p-4 bg-green-50 rounded-lg">
                    <div class="text-2xl mb-2">✅</div>
                    <div class="font-semibold">Edge 79+</div>
                </div>
            </div>
            <p class="text-gray-600 text-sm mt-4 text-center">
                Requires modern browser with ES6+ support and Local Storage API
            </p>
        </section>

        <!-- Contributing -->
        <section id="contributing" class="section bg-white rounded-lg shadow-lg p-8 mb-8">
            <h2 class="text-3xl font-bold text-gray-800 mb-6">🤝 Contributing</h2>
            <div class="space-y-4">
                <p class="text-gray-700">
                    We welcome contributions! Here's how you can help improve Web Writer:
                </p>
                <ul class="list-disc list-inside space-y-2 text-gray-700">
                    <li>Report bugs and suggest features</li>
                    <li>Improve documentation</li>
                    <li>Add new export formats</li>
                    <li>Enhance accessibility features</li>
                    <li>Optimize performance</li>
                </ul>
                <div class="bg-blue-50 p-4 rounded-lg">
                    <h4 class="font-semibold text-blue-800 mb-2">Development Guidelines</h4>
                    <ul class="list-disc list-inside space-y-1 text-blue-700 text-sm">
                        <li>Keep it vanilla - no external dependencies except Tailwind CSS</li>
                        <li>Maintain responsive design principles</li>
                        <li>Ensure accessibility compliance</li>
                        <li>Test across multiple browsers</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Footer -->
        <footer class="text-center py-8">
            <div class="bg-white rounded-lg shadow-lg p-6">
                <p class="text-gray-600 mb-4">
                    Made with ❤️ for writers everywhere
                </p>
                <div class="flex justify-center gap-4 text-sm">
                    <span class="text-gray-500">Version 1.0.0</span>
                    <span class="text-gray-300">•</span>
                    <span class="text-gray-500">MIT License</span>
                    <span class="text-gray-300">•</span>
                    <span class="text-gray-500">No Dependencies</span>
                </div>
            </div>
        </footer>
    </div>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                }
            });
        });

        // Add copy functionality to code blocks
        document.querySelectorAll('.code-block').forEach(block => {
            block.addEventListener('click', function() {
                navigator.clipboard.writeText(this.textContent).then(() => {
                    const originalBg = this.style.backgroundColor;
                    this.style.backgroundColor = '#10b981';
                    setTimeout(() => {
                        this.style.backgroundColor = originalBg;
                    }, 200);
                });
            });
            
            // Add cursor pointer and title
            block.style.cursor = 'pointer';
            block.title = 'Click to copy';
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'987c9d0df512893d',t:'MTc1OTMyODU2MC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
# tayokelay2k.github.io
