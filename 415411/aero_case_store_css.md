/* STREAMING_CHUNK:Importing typography and base styles */
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap');

body {
    background-color: #0a0b10;
    color: #f3f4f6;
    font-family: 'Inter', sans-serif;
    overflow-x: hidden;
}

/* STREAMING_CHUNK:Styling glassmorphism panels and effects */
.glass-panel {
    background: rgba(18, 20, 28, 0.75);
    backdrop-filter: blur(16px);
    -webkit-backdrop-filter: blur(16px);
    border: 1px solid rgba(255, 255, 255, 0.08);
}

.glass-nav {
    background: rgba(10, 11, 16, 0.85);
    backdrop-filter: blur(20px);
    -webkit-backdrop-filter: blur(20px);
    border-bottom: 1px solid rgba(0, 240, 255, 0.15);
}

.hero-glow {
    position: absolute;
    width: 600px;
    height: 600px;
    background: radial-gradient(circle, rgba(0, 240, 255, 0.12) 0%, rgba(112, 0, 255, 0.05) 50%, transparent 70%);
    z-index: 0;
    pointer-events: none;
}

.text-gradient {
    background: linear-gradient(135deg, #00f0ff 0%, #7000ff 50%, #ff0055 100%);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}

.card-hover {
    transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
}

.card-hover:hover {
    transform: translateY(-8px);
    border-color: rgba(0, 240, 255, 0.5);
    box-shadow: 0 20px 40px -15px rgba(0, 240, 255, 0.2);
}

/* STREAMING_CHUNK:Customizing custom scrollbar */
::-webkit-scrollbar {
    width: 8px;
}
::-webkit-scrollbar-track {
    background: #0a0b10;
}
::-webkit-scrollbar-thumb {
    background: #1e2230;
    border-radius: 4px;
}
::-webkit-scrollbar-thumb:hover {
    background: #00f0ff;
}