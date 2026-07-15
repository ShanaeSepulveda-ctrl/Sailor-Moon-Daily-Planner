<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sailor Moon Daily Planner</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Nunito:wght@400;600;700;800&family=Pacifico&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            font-family: 'Nunito', sans-serif;
            background: linear-gradient(135deg, #ffc3a0 0%, #ffafbd 25%, #d4a5ff 75%, #a1c4fd 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
            color: #4a4a4a;
        }

        /* Magical Starry Background Overlay */
        .stars-overlay {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            background-image: 
                radial-gradient(2px 2px at 20px 30px, #ffffff, rgba(0,0,0,0)),
                radial-gradient(2px 2px at 40px 70px, #ffffff, rgba(0,0,0,0)),
                radial-gradient(3px 3px at 90px 40px, #ffffff, rgba(0,0,0,0)),
                radial-gradient(2px 2px at 160px 120px, #ffffff, rgba(0,0,0,0));
            background-repeat: repeat;
            background-size: 200px 200px;
            opacity: 0.4;
            animation: twinkle 4s infinite alternate;
        }

        @keyframes twinkle {
            0% { opacity: 0.2; }
            100% { opacity: 0.6; }
        }

        /* Glassmorphism Card */
        .glass-card {
            background: rgba(255, 255, 255, 0.75);
            backdrop-filter: blur(12px);
            -webkit-backdrop-filter: blur(12px);
            border: 2px solid rgba(255, 255, 255, 0.5);
            box-shadow: 0 8px 32px rgba(255, 105, 180, 0.2);
            border-radius: 24px;
            width: 100%;
            max-width: 600px;
            overflow: hidden;
            position: relative;
            z-index: 10;
        }

        .title-font {
            font-family: 'Pacifico', cursive;
            background: -webkit-linear-gradient(45deg, #ff6b6b, #c06c84);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .task-item {
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            border: 2px solid transparent;
        }
        
        .task-item:hover {
            transform: translateY(-2px);
            box-shadow: 0 6px 16px rgba(255, 182, 193, 0.4);
            border-color: rgba(255, 182, 193, 0.5);
            background: rgba(255, 255, 255, 0.9);
        }

        .task-item.completed {
            opacity: 0.6;
            background: rgba(243, 244, 246, 0.6);
        }

        .task-item.completed .task-title {
            text-decoration: line-through;
            color: #9ca3af;
        }

        /* Custom Star Checkbox */
        .star-checkbox {
            appearance: none;
            width: 28px;
            height: 28px;
            background-color: #fff;
            border: 2px solid #ffafbd;
            border-radius: 50%;
            cursor: pointer;
            position: relative;
            outline: none;
            transition: all 0.3s ease;
            flex-shrink: 0;
            box-shadow: inset 0 2px 4px rgba(0,0,0,0.05);
        }

        .star-checkbox:checked {
            background-color: #ffd700;
            border-color: #ffd700;
            box-shadow: 0 0 10px rgba(255, 215, 0, 0.6);
        }

        .star-checkbox:checked::after {
            content: '⭐';
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 16px;
            line-height: 1;
        }

        /* Urgency Pills */
        .badge-high { background: linear-gradient(135deg, #ff758c 0%, #ff7eb3 100%); color: white; }
        .badge-medium { background: linear-gradient(135deg, #b224ef 0%, #7579ff 100%); color: white; }
        .badge-low { background: linear-gradient(135deg, #89f7fe 0%, #66a6ff 100%); color: white; }

        /* Filter Buttons */
        .filter-btn {
            transition: all 0.2s ease;
            background: rgba(255,255,255,0.5);
            color: #6b7280;
        }
        .filter-btn:hover {
            background: rgba(255,255,255,0.9);
            color: #ff6b6b;
        }
        .filter-btn.active {
            background: #ffafbd;
            color: white;
            font-weight: 700;
            box-shadow: 0 4px 10px rgba(255, 175, 189, 0.4);
        }

        /* Progress Bar */
        .progress-container {
            height: 12px;
            background: rgba(255, 255, 255, 0.5);
            border-radius: 10px;
            overflow: hidden;
            box-shadow: inset 0 1px 3px rgba(0,0,0,0.1);
        }
        .progress-bar {
            height: 100%;
            background: linear-gradient(90deg, #ffafbd 0%, #ffc3a0 100%);
            width: 0%;
            transition: width 0.5s cubic-bezier(0.4, 0, 0.2, 1);
            position: relative;
        }
        .progress-bar::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: linear-gradient(90deg, transparent, rgba(255,255,255,0.4), transparent);
            animation: shimmer 1.5s infinite;
        }

        @keyframes shimmer {
            0% { transform: translateX(-100%); }
            100% { transform: translateX(100%); }
        }
    </style>
</head>
<body>

    <div class="stars-overlay"></div>

    <div class="glass-card flex flex-col h-[700px]">
        <!-- Header -->
        <div class="p-6 border-b border-white/40 bg-white/30 text-center relative">
            <h1 class="title-font text-4xl mb-2 flex items-center justify-center gap-3">
                <span>🌙</span> Magical Missions <span>✨</span>
            </h1>
            <p class="text-sm font-semibold text-pink-500 tracking-wide uppercase">Tuesday, July 14, 2026</p>
            
            <div class="mt-5">
                <div class="flex justify-between text-xs font-bold text-gray-500 mb-1 px-1">
                    <span>Moon Power Level</span>
                    <span id="progress-text">0%</span>
                </div>
                <div class="progress-container">
                    <div class="progress-bar" id="progress-bar"></div>
                </div>
            </div>
        </div>

        <!-- Filters -->
        <div class="px-6 py-4 flex gap-2 overflow-x-auto border-b border-white/40 bg-white/10">
            <button class="filter-btn active px-4 py-1.5 rounded-full text-sm font-bold shadow-sm" data-filter="All">All Magic</button>
            <button class="filter-btn px-4 py-1.5 rounded-full text-sm font-bold shadow-sm" data-filter="High">💖 Critical</button>
            <button class="filter-btn px-4 py-1.5 rounded-full text-sm font-bold shadow-sm" data-filter="Medium">🔮 Important</button>
        </div>

        <!-- Task List -->
        <div class="flex-1 overflow-y-auto p-6 space-y-4" id="task-list">
            <!-- Tasks injected via JS -->
        </div>
        
        <!-- Footer -->
        <div class="p-4 bg-white/40 text-center border-t border-white/40 text-xs font-bold text-purple-400">
            "In the name of the Moon, you will conquer today!" 🎀
        </div>
    </div>

    <script>
        const initialTasks = [
            { 
                id: 1, 
                title: "Review FAMLI+ & Leave Docs", 
                desc: "Check the pending task notification and review leave documentation requirements.", 
                urgency: "High", 
                completed: false 
            },
            { 
                id: 2, 
                title: "Submit Klaus's Health Appraisal", 
                desc: "Send the completed health form from yesterday's appointment to Britt.", 
                urgency: "High", 
                completed: false 
            },
            { 
                id: 3, 
                title: "Delegate NY Flights to Tuxedo Mask (Kris)", 
                desc: "Toss a rose and remind him to book the return flights for August 20th.", 
                urgency: "Medium", 
                completed: false 
            },
            { 
                id: 4, 
                title: "Moon Healing Escalation 🌙", 
                desc: "Keep your arm immobilized, rest, and prepare for your post-op appt on Friday.", 
                urgency: "High", 
                completed: false 
            }
        ];

        let state = {
            tasks: [...initialTasks],
            filter: 'All'
        };

        const taskListEl = document.getElementById('task-list');
        const progressBarEl = document.getElementById('progress-bar');
        const progressTextEl = document.getElementById('progress-text');
        const filterBtns = document.querySelectorAll('.filter-btn');

        function updateProgress() {
            const total = state.tasks.length;
            if (total === 0) return;
            const completed = state.tasks.filter(t => t.completed).length;
            const pct = Math.round((completed / total) * 100);
            
            progressBarEl.style.width = `${pct}%`;
            progressTextEl.innerText = `${pct}% Ready`;
        }

        function toggleTask(id) {
            state.tasks = state.tasks.map(t => 
                t.id === id ? { ...t, completed: !t.completed } : t
            );
            renderTasks();
            updateProgress();
        }

        function getBadgeClass(urgency) {
            if (urgency === 'High') return 'badge-high';
            if (urgency === 'Medium') return 'badge-medium';
            return 'badge-low';
        }

        function getUrgencyIcon(urgency) {
            if (urgency === 'High') return '💖';
            if (urgency === 'Medium') return '🔮';
            return '💧';
        }

        function renderTasks() {
            taskListEl.innerHTML = '';
            
            const filteredTasks = state.tasks.filter(t => {
                if (state.filter === 'All') return true;
                return t.urgency === state.filter;
            });

            if (filteredTasks.length === 0) {
                taskListEl.innerHTML = `
                    <div class="text-center py-10 text-pink-400 font-bold opacity-70">
                        <div class="text-4xl mb-3">✨</div>
                        No tasks in this category!
                    </div>
                `;
                return;
            }

            filteredTasks.forEach(task => {
                const item = document.createElement('div');
                item.className = `task-item bg-white/60 backdrop-blur p-4 rounded-2xl flex items-start gap-4 shadow-sm cursor-pointer ${task.completed ? 'completed' : ''}`;
                item.onclick = (e) => {
                    // Prevent double-firing if clicking exactly on the checkbox
                    if (e.target !== item.querySelector('input')) {
                        toggleTask(task.id);
                    }
                };

                item.innerHTML = `
                    <input type="checkbox" class="star-checkbox mt-1" ${task.completed ? 'checked' : ''} onclick="event.stopPropagation(); toggleTask(${task.id})">
                    <div class="flex-1 min-w-0 pt-0.5">
                        <div class="flex items-center justify-between gap-2 mb-1">
                            <h3 class="task-title font-bold text-gray-800 leading-tight">${task.title}</h3>
                            <span class="${getBadgeClass(task.urgency)} text-[10px] uppercase tracking-wider font-extrabold px-2 py-0.5 rounded-full flex-shrink-0 flex items-center gap-1 shadow-sm">
                                ${task.urgency}
                            </span>
                        </div>
                        <p class="text-sm text-gray-600 leading-snug">${task.desc}</p>
                    </div>
                `;
                
                taskListEl.appendChild(item);
            });
        }

        // Event Listeners for Filters
        filterBtns.forEach(btn => {
            btn.addEventListener('click', (e) => {
                filterBtns.forEach(b => b.classList.remove('active'));
                e.target.classList.add('active');
                state.filter = e.target.dataset.filter;
                renderTasks();
            });
        });

        // Init
        renderTasks();
        updateProgress();

    </script>
</body>
</html>
