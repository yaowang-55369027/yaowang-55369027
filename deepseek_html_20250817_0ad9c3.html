<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>科学小达人 - 五年级科学闯关答题</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Comic Sans MS', 'Microsoft YaHei', sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #1a2980, #26d0ce);
            min-height: 100vh;
            padding: 20px;
            color: #333;
            display: flex;
            flex-direction: column;
            align-items: center;
            position: relative;
            overflow-x: hidden;
        }
        
        /* GitHub DOCTYPE 修复 */
        body::before {
            content: "";
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.9);
            z-index: 9999;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            font-size: 1.5rem;
            text-align: center;
            padding: 20px;
            pointer-events: none;
            opacity: 0;
            transition: opacity 0.5s;
        }
        
        body.show-doctype-warning::before {
            content: "检测到页面渲染问题，正在修复...";
            opacity: 1;
        }
        
        /* 欢迎界面 */
        .welcome-screen {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: #1a2980;
            background: linear-gradient(135deg, #1a2980, #26d0ce);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            z-index: 100;
            text-align: center;
            padding: 20px;
            transition: opacity 0.8s, transform 0.8s;
        }
        
        .welcome-overlay {
            background: rgba(0, 30, 60, 0.85);
            padding: 40px;
            border-radius: 25px;
            max-width: 800px;
            width: 90%;
            box-shadow: 0 15px 50px rgba(0, 0, 0, 0.5);
        }
        
        .welcome-title {
            font-size: 3.5rem;
            color: #fff;
            margin-bottom: 20px;
            text-shadow: 0 2px 8px rgba(0, 0, 0, 0.6);
        }
        
        .welcome-subtitle {
            font-size: 1.8rem;
            color: #ffd166;
            margin-bottom: 30px;
        }
        
        .game-instructions {
            background: rgba(255, 255, 255, 0.9);
            border-radius: 15px;
            padding: 25px;
            margin: 25px 0;
            text-align: left;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        
        .game-instructions h3 {
            color: #1a2980;
            margin-bottom: 15px;
            text-align: center;
            font-size: 1.8rem;
        }
        
        .instruction-item {
            display: flex;
            margin: 15px 0;
            align-items: flex-start;
        }
        
        .instruction-item i {
            font-size: 1.5rem;
            color: #06d6a0;
            min-width: 40px;
            padding-top: 5px;
        }
        
        .start-btn {
            padding: 18px 50px;
            font-size: 1.8rem;
            background: linear-gradient(to right, #ff6b6b, #ff8e53);
            color: white;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            font-weight: bold;
            transition: all 0.3s ease;
            margin-top: 20px;
            box-shadow: 0 8px 20px rgba(255, 107, 107, 0.5);
        }
        
        .start-btn:hover {
            transform: translateY(-5px) scale(1.05);
            box-shadow: 0 12px 25px rgba(255, 107, 107, 0.7);
        }
        
        /* 主游戏容器 */
        .header {
            text-align: center;
            margin: 20px 0;
            color: white;
            text-shadow: 0 2px 4px rgba(0,0,0,0.2);
            width: 100%;
            max-width: 900px;
            display: none;
        }
        
        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        .header p {
            font-size: 1.2rem;
            max-width: 700px;
            margin: 0 auto;
        }
        
        .container {
            display: flex;
            flex-direction: column;
            width: 100%;
            max-width: 900px;
            background: white;
            border-radius: 20px;
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.25);
            overflow: hidden;
            margin-bottom: 30px;
            display: none;
        }
        
        .game-tabs {
            display: flex;
            background: linear-gradient(90deg, #ff6b6b, #ff8e53);
        }
        
        .tab {
            flex: 1;
            text-align: center;
            padding: 15px;
            font-size: 1.2rem;
            font-weight: bold;
            color: white;
            cursor: pointer;
            transition: all 0.3s ease;
            border-bottom: 4px solid transparent;
        }
        
        .tab.active {
            background: rgba(255, 255, 255, 0.2);
            border-bottom: 4px solid #ffd166;
        }
        
        .tab:hover:not(.active) {
            background: rgba(255, 255, 255, 0.1);
        }
        
        .tab-content {
            display: none;
            padding: 25px;
        }
        
        #game-tab {
            display: block;
        }
        
        .stats {
            display: flex;
            justify-content: space-between;
            width: 100%;
            margin-bottom: 20px;
            padding: 15px;
            background-color: #f0f7ff;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        
        .stat-item {
            text-align: center;
            flex: 1;
        }
        
        .stat-value {
            font-size: 1.8rem;
            font-weight: bold;
            color: #ff6b6b;
        }
        
        .stat-label {
            font-size: 0.9rem;
            color: #666;
        }
        
        .question-container {
            background: white;
            border-radius: 15px;
            padding: 25px;
            width: 100%;
            margin-bottom: 25px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            border: 2px solid #e0e7ff;
            position: relative;
        }
        
        .question-number {
            position: absolute;
            top: -15px;
            left: 20px;
            background: #4e89ae;
            color: white;
            padding: 5px 15px;
            border-radius: 20px;
            font-weight: bold;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        .question-text {
            font-size: 1.4rem;
            margin-bottom: 25px;
            line-height: 1.5;
            color: #2c3e50;
        }
        
        .options-container {
            display: grid;
            grid-template-columns: 1fr;
            gap: 12px;
            width: 100%;
        }
        
        .option {
            background: linear-gradient(to bottom, #f9f9f9, #eef2f7);
            border: 2px solid #d1e3ff;
            border-radius: 12px;
            padding: 15px;
            font-size: 1.1rem;
            cursor: pointer;
            transition: all 0.3s ease;
            text-align: center;
        }
        
        .option:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            background: linear-gradient(to bottom, #e6f7ff, #d1e8ff);
            border-color: #4dabf7;
        }
        
        .option.correct {
            background: linear-gradient(to bottom, #69db7c, #40c057);
            color: white;
            border-color: #2f9e44;
        }
        
        .option.wrong {
            background: linear-gradient(to bottom, #ff8787, #fa5252);
            color: white;
            border-color: #e03131;
        }
        
        .controls {
            display: flex;
            justify-content: center;
            gap: 15px;
            width: 100%;
            margin-top: 20px;
        }
        
        .btn {
            padding: 14px 30px;
            font-size: 1.1rem;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            font-weight: bold;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
            gap: 8px;
        }
        
        .btn-primary {
            background: linear-gradient(to right, #4facfe, #00f2fe);
            color: white;
            box-shadow: 0 4px 10px rgba(79, 172, 254, 0.4);
        }
        
        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 15px rgba(79, 172, 254, 0.6);
        }
        
        .btn-secondary {
            background: linear-gradient(to right, #ff9a9e, #fad0c4);
            color: white;
            box-shadow: 0 4px 10px rgba(255, 154, 158, 0.4);
        }
        
        .btn-secondary:hover {
            transform: translateY(-3px);
            box-shadow: 0 6px 15px rgba(255, 154, 158, 0.6);
        }
        
        .wrong-questions {
            padding: 25px;
        }
        
        .wrong-questions h2 {
            color: #ff6b6b;
            margin-bottom: 20px;
            text-align: center;
            padding-bottom: 15px;
            border-bottom: 2px solid #ffd166;
        }
        
        .wrong-list {
            display: grid;
            grid-template-columns: 1fr;
            gap: 20px;
        }
        
        .wrong-item {
            background: #fff5f5;
            border-radius: 12px;
            padding: 20px;
            border-left: 4px solid #ff6b6b;
        }
        
        .wrong-item h3 {
            color: #ff6b6b;
            margin-bottom: 10px;
        }
        
        .wrong-options {
            display: flex;
            gap: 10px;
            margin: 10px 0;
            flex-wrap: wrap;
        }
        
        .wrong-option {
            padding: 8px 15px;
            border-radius: 20px;
            background: #ffe3e3;
            font-size: 0.9rem;
        }
        
        .wrong-option.correct {
            background: #d3f9d8;
            color: #2b8a3e;
        }
        
        .no-wrong {
            text-align: center;
            padding: 40px;
            color: #666;
            font-size: 1.2rem;
            grid-column: 1 / -1;
        }
        
        .pagination {
            display: flex;
            justify-content: center;
            margin-top: 25px;
            gap: 10px;
        }
        
        .page-btn {
            padding: 8px 15px;
            background: #4facfe;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: all 0.3s;
        }
        
        .page-btn:hover:not(:disabled) {
            background: #3a9bf7;
            transform: translateY(-2px);
        }
        
        .page-btn:disabled {
            background: #cccccc;
            cursor: not-allowed;
        }
        
        .current-page {
            padding: 8px 15px;
            background: #ff6b6b;
            color: white;
            border-radius: 5px;
        }
        
        /* 弹窗样式 */
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.7);
            z-index: 1000;
            justify-content: center;
            align-items: center;
        }
        
        .modal-content {
            background: white;
            border-radius: 20px;
            padding: 30px;
            max-width: 600px;
            width: 90%;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.4);
            position: relative;
            animation: popIn 0.5s ease-out;
        }
        
        @keyframes popIn {
            0% { transform: scale(0.8); opacity: 0; }
            100% { transform: scale(1); opacity: 1; }
        }
        
        .modal-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
            padding-bottom: 15px;
            border-bottom: 2px solid #f0f0f0;
        }
        
        .modal-title {
            font-size: 1.8rem;
            color: #ff6b6b;
        }
        
        .close-btn {
            background: none;
            border: none;
            font-size: 1.8rem;
            cursor: pointer;
            color: #999;
            transition: color 0.3s;
        }
        
        .close-btn:hover {
            color: #ff6b6b;
        }
        
        .modal-body {
            font-size: 1.1rem;
            line-height: 1.6;
            margin-bottom: 25px;
        }
        
        .modal-footer {
            display: flex;
            justify-content: flex-end;
        }
        
        .modal-btn {
            padding: 10px 25px;
            font-size: 1rem;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            font-weight: bold;
            transition: all 0.3s ease;
        }
        
        /* AI助手 */
        .ai-assistant {
            position: fixed;
            bottom: 30px;
            right: 30px;
            z-index: 500;
        }
        
        .ai-icon {
            width: 70px;
            height: 70px;
            background: linear-gradient(135deg, #6a11cb, #2575fc);
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            cursor: pointer;
            box-shadow: 0 5px 20px rgba(0, 0, 0, 0.3);
            transition: all 0.3s ease;
        }
        
        .ai-icon:hover {
            transform: scale(1.1) rotate(10deg);
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.4);
        }
        
        .ai-icon i {
            font-size: 32px;
            color: white;
        }
        
        .ai-chatbox {
            position: absolute;
            bottom: 90px;
            right: 0;
            width: 350px;
            background: white;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            display: none;
            flex-direction: column;
            overflow: hidden;
        }
        
        .ai-header {
            background: linear-gradient(90deg, #6a11cb, #2575fc);
            color: white;
            padding: 15px;
            font-weight: bold;
            font-size: 1.2rem;
        }
        
        .ai-messages {
            height: 300px;
            padding: 15px;
            overflow-y: auto;
            background: #f9f9f9;
        }
        
        .ai-message {
            margin-bottom: 15px;
            padding: 10px 15px;
            border-radius: 10px;
            max-width: 80%;
        }
        
        .ai-message.bot {
            background: #e6f7ff;
            align-self: flex-start;
            border-bottom-left-radius: 2px;
        }
        
        .ai-message.user {
            background: #d1e8ff;
            align-self: flex-end;
            margin-left: auto;
            border-bottom-right-radius: 2px;
        }
        
        .ai-input {
            display: flex;
            padding: 15px;
            background: #f0f0f0;
            border-top: 1px solid #ddd;
        }
        
        .ai-input input {
            flex: 1;
            padding: 12px;
            border: 1px solid #ddd;
            border-radius: 25px;
            outline: none;
            font-size: 1rem;
        }
        
        .ai-input button {
            background: #4facfe;
            color: white;
            border: none;
            border-radius: 25px;
            padding: 10px 20px;
            margin-left: 10px;
            cursor: pointer;
            transition: background 0.3s;
        }
        
        .ai-input button:hover {
            background: #3a9bf7;
        }
        
        /* 响应式设计 */
        @media (max-width: 768px) {
            .welcome-title {
                font-size: 2.5rem;
            }
            
            .welcome-subtitle {
                font-size: 1.4rem;
            }
            
            .header h1 {
                font-size: 1.8rem;
            }
            
            .question-text {
                font-size: 1.2rem;
            }
            
            .stats {
                flex-direction: column;
                gap: 15px;
            }
            
            .tab {
                font-size: 1rem;
                padding: 12px 5px;
            }
            
            .ai-chatbox {
                width: 300px;
            }
            
            .ai-icon {
                width: 60px;
                height: 60px;
            }
            
            .start-btn {
                font-size: 1.5rem;
                padding: 15px 30px;
            }
        }
        
        @media (max-width: 480px) {
            .welcome-title {
                font-size: 2rem;
            }
            
            .welcome-subtitle {
                font-size: 1.2rem;
            }
            
            .game-instructions {
                padding: 15px;
            }
            
            .modal-content {
                padding: 20px;
            }
            
            .ai-chatbox {
                width: 280px;
            }
        }
    </style>
</head>
<body>
    <!-- 欢迎界面 -->
    <div class="welcome-screen" id="welcome-screen">
        <div class="welcome-overlay">
            <h1 class="welcome-title">科学小达人闯关挑战</h1>
            <p class="welcome-subtitle">探索科学奥秘，成为科学小专家！</p>
            
            <div class="game-instructions">
                <h3>游戏说明</h3>
                <div class="instruction-item">
                    <i class="fas fa-gamepad"></i>
                    <div>
                        <strong>闯关模式：</strong> 游戏包含多个关卡，每个关卡有3道科学题目，答对题目获得积分
                    </div>
                </div>
                <div class="instruction-item">
                    <i class="fas fa-lightbulb"></i>
                    <div>
                        <strong>知识点解析：</strong> 答错题目时会弹出知识点解析，帮助理解科学原理
                    </div>
                </div>
                <div class="instruction-item">
                    <i class="fas fa-book"></i>
                    <div>
                        <strong>错题本功能：</strong> 所有答错的题目会自动记录到错题本，方便复习巩固
                    </div>
                </div>
                <div class="instruction-item">
                    <i class="fas fa-robot"></i>
                    <div>
                        <strong>AI科学助手：</strong> 随时点击右下角机器人图标获取科学问题解答
                    </div>
                </div>
                <div class="instruction-item">
                    <i class="fas fa-trophy"></i>
                    <div>
                        <strong>成就系统：</strong> 完成关卡获得积分，解锁科学小达人称号
                    </div>
                </div>
            </div>
            
            <button class="start-btn" id="start-btn">
                <i class="fas fa-play"></i> 开始闯关
            </button>
        </div>
    </div>
    
    <!-- 主游戏界面 -->
    <div class="header">
        <h1><i class="fas fa-flask"></i> 科学小达人闯关挑战</h1>
        <p>在趣味答题中巩固科学知识，成为科学小达人！</p>
    </div>
    
    <div class="container">
        <div class="game-tabs">
            <div class="tab active" data-tab="game">答题闯关</div>
            <div class="tab" data-tab="wrong">错题本</div>
        </div>
        
        <!-- 答题闯关页面 -->
        <div class="tab-content" id="game-tab">
            <div class="stats">
                <div class="stat-item">
                    <div class="stat-value" id="level">1</div>
                    <div class="stat-label">当前关卡</div>
                </div>
                <div class="stat-item">
                    <div class="stat-value" id="score">0</div>
                    <div class="stat-label">得分</div>
                </div>
                <div class="stat-item">
                    <div class="stat-value" id="correct-count">0</div>
                    <div class="stat-label">答对题数</div>
                </div>
                <div class="stat-item">
                    <div class="stat-value" id="wrong-count">0</div>
                    <div class="stat-label">错题数</div>
                </div>
            </div>
            
            <div class="question-container">
                <div class="question-number">第 <span id="question-num">1</span> 题</div>
                <div class="question-text" id="question-text">当光线照射到平面镜上时，会发生什么现象？</div>
                
                <div class="options-container">
                    <div class="option" data-value="A">A. 折射</div>
                    <div class="option" data-value="B">B. 反射</div>
                    <div class="option" data-value="C">C. 透射</div>
                </div>
            </div>
            
            <div class="controls">
                <button class="btn btn-primary" id="next-btn">
                    <i class="fas fa-arrow-right"></i> 下一题
                </button>
            </div>
        </div>
        
        <!-- 错题本页面 -->
        <div class="tab-content" id="wrong-tab">
            <div class="wrong-questions">
                <h2><i class="fas fa-book-open"></i> 我的科学错题本</h2>
                <div class="wrong-list" id="wrong-list">
                    <div class="no-wrong">
                        <i class="fas fa-smile-beam" style="font-size: 3rem; color: #ffd166; margin-bottom: 15px;"></i>
                        <p>目前还没有错题，继续加油！</p>
                    </div>
                </div>
                
                <div class="pagination" id="pagination" style="display: none;">
                    <button class="page-btn" id="prev-btn">上一页</button>
                    <div class="current-page">第 <span id="current-page">1</span> 页</div>
                    <button class="page-btn" id="next-page-btn">下一页</button>
                </div>
            </div>
        </div>
    </div>
    
    <!-- 知识点解析弹窗 -->
    <div class="modal" id="explanation-modal">
        <div class="modal-content">
            <div class="modal-header">
                <h3 class="modal-title"><i class="fas fa-lightbulb"></i> 知识点解析</h3>
                <button class="close-btn" id="close-explanation">&times;</button>
            </div>
            <div class="modal-body" id="explanation-text">
                当光线照射到平面镜上时，会发生反射现象。反射是指光线在遇到光滑表面时，按照入射角等于反射角的规律返回的现象。平面镜是典型的反射面，能够将光线反射回去。
            </div>
            <div class="modal-footer">
                <button class="modal-btn btn-primary" id="continue-btn">继续答题</button>
            </div>
        </div>
    </div>
    
    <!-- 闯关完成弹窗 -->
    <div class="modal" id="result-modal">
        <div class="modal-content">
            <div class="modal-header">
                <h3 class="modal-title"><i class="fas fa-trophy"></i> 闯关完成！</h3>
                <button class="close-btn" id="close-result">&times;</button>
            </div>
            <div class="modal-body">
                <div style="text-align: center; margin: 20px 0;">
                    <i class="fas fa-medal" style="font-size: 4rem; color: #ffd166;"></i>
                </div>
                <div style="background: #f0f7ff; border-radius: 15px; padding: 20px; margin: 20px 0;">
                    <p style="text-align: center; margin-bottom: 15px; font-size: 1.2rem;">成绩统计</p>
                    <div style="display: flex; justify-content: space-around; text-align: center;">
                        <div>
                            <div style="font-size: 2rem; color: #4facfe; font-weight: bold;" id="final-score">0</div>
                            <div>总得分</div>
                        </div>
                        <div>
                            <div style="font-size: 2rem; color: #06d6a0; font-weight: bold;" id="final-correct">0</div>
                            <div>答对题数</div>
                        </div>
                        <div>
                            <div style="font-size: 2rem; color: #ff6b6b; font-weight: bold;" id="final-wrong">0</div>
                            <div>错题数</div>
                        </div>
                    </div>
                </div>
                <p style="text-align: center; font-size: 1.2rem; margin-top: 20px;" id="result-message">
                    恭喜你完成所有关卡！继续加油成为科学小达人！
                </p>
            </div>
            <div class="modal-footer" style="justify-content: center;">
                <button class="modal-btn btn-primary" id="restart-btn" style="margin-right: 10px;">
                    <i class="fas fa-redo"></i> 再玩一次
                </button>
                <button class="modal-btn btn-secondary" id="review-wrong">
                    <i class="fas fa-book"></i> 复习错题
                </button>
            </div>
        </div>
    </div>
    
    <!-- AI助手 -->
    <div class="ai-assistant">
        <div class="ai-icon" id="ai-icon">
            <i class="fas fa-robot"></i>
        </div>
        <div class="ai-chatbox" id="ai-chatbox">
            <div class="ai-header">
                <i class="fas fa-robot"></i> 科学小助手
            </div>
            <div class="ai-messages" id="ai-messages">
                <div class="ai-message bot">
                    你好！我是科学小助手，有什么科学问题都可以问我哦！
                </div>
            </div>
            <div class="ai-input">
                <input type="text" id="ai-input" placeholder="输入科学问题...">
                <button id="ai-send"><i class="fas fa-paper-plane"></i></button>
            </div>
        </div>
    </div>

    <!-- 字体图标备用方案 -->
    <div style="display:none;">
        <i class="fas fa-flask"></i>
        <i class="fas fa-play"></i>
        <i class="fas fa-gamepad"></i>
        <i class="fas fa-lightbulb"></i>
        <i class="fas fa-book"></i>
        <i class="fas fa-robot"></i>
        <i class="fas fa-trophy"></i>
        <i class="fas fa-smile-beam"></i>
        <i class="fas fa-book-open"></i>
        <i class="fas fa-arrow-right"></i>
        <i class="fas fa-redo"></i>
        <i class="fas fa-medal"></i>
        <i class="fas fa-paper-plane"></i>
    </div>

    <script>
        // 解决GitHub显示DOCTYPE问题
        function fixGitHubRendering() {
            // 检查是否在GitHub环境中
            if (window.location.hostname.includes('github.io') || 
                document.documentElement.outerHTML.includes('<!DOCTYPE html>')) {
                
                // 显示修复提示
                document.body.classList.add('show-doctype-warning');
                
                // 添加延迟让用户看到提示
                setTimeout(() => {
                    // 移除所有不需要的节点
                    const bodyChildren = document.body.children;
                    for (let i = bodyChildren.length - 1; i >= 0; i--) {
                        const node = bodyChildren[i];
                        if (node.nodeType === Node.COMMENT_NODE || 
                            (node.nodeType === Node.TEXT_NODE && node.textContent.trim() === '')) {
                            document.body.removeChild(node);
                        }
                    }
                    
                    // 隐藏提示
                    document.body.classList.remove('show-doctype-warning');
                }, 1500);
            }
        }
        
        // 科学题库（每题3个选项）
        const scienceQuestions = [
            {
                question: "当光线照射到平面镜上时，会发生什么现象？",
                options: ["A. 折射", "B. 反射", "C. 透射"],
                correctAnswer: "B",
                explanation: "当光线照射到平面镜上时，会发生反射现象。反射是指光线在遇到光滑表面时，按照入射角等于反射角的规律返回的现象。平面镜是典型的反射面，能够将光线反射回去。"
            },
            {
                question: "植物进行光合作用的主要场所是哪里？",
                options: ["A. 根", "B. 茎", "C. 叶"],
                correctAnswer: "C",
                explanation: "植物进行光合作用的主要场所是叶。叶中含有叶绿体，叶绿体是光合作用的场所，能够利用光能将二氧化碳和水转化为有机物，并释放氧气。"
            },
            {
                question: "力的作用效果有哪些？",
                options: ["A. 改变物体形状", "B. 改变运动状态", "C. A和B"],
                correctAnswer: "C",
                explanation: "力的作用效果主要有两个：一是改变物体的形状，使物体发生形变；二是改变物体的运动状态，包括使物体从静止变为运动，从运动变为静止，或改变物体运动的速度和方向。"
            },
            {
                question: "下列哪种物质是绝缘体？",
                options: ["A. 铜", "B. 铁", "C. 橡胶"],
                correctAnswer: "C",
                explanation: "橡胶是绝缘体，不容易导电。而铜、铁是导体，容易导电。绝缘体在电路中用于防止电流流向不需要的地方，保证用电安全。"
            },
            {
                question: "水在自然界中的循环过程不包括以下哪个环节？",
                options: ["A. 蒸发", "B. 光合作用", "C. 降水"],
                correctAnswer: "B",
                explanation: "水循环的主要过程包括蒸发（水变成水蒸气）、凝结（水蒸气变成小水滴）、降水（雨、雪等）以及径流等环节。光合作用是植物制造有机物的过程，不属于水循环环节。"
            },
            {
                question: "下列哪种动物属于哺乳动物？",
                options: ["A. 鳄鱼", "B. 鲸鱼", "C. 企鹅"],
                correctAnswer: "B",
                explanation: "鲸鱼属于哺乳动物，它们用肺呼吸，胎生，用乳汁哺育幼崽。鳄鱼属于爬行动物，企鹅属于鸟类。"
            },
            {
                question: "食物在人体内消化的主要场所是？",
                options: ["A. 口腔", "B. 胃", "C. 小肠"],
                correctAnswer: "C",
                explanation: "小肠是食物消化和吸收的主要场所。口腔进行初步消化，胃进行蛋白质的初步分解，而大部分营养物质都是在小肠被消化和吸收的。"
            },
            {
                question: "下列能源中，属于可再生能源的是？",
                options: ["A. 煤炭", "B. 石油", "C. 太阳能"],
                correctAnswer: "C",
                explanation: "太阳能是可再生能源，可以持续利用。煤炭、石油是化石能源，形成需要数百万年，属于不可再生能源。"
            },
            {
                question: "声音在下列哪种介质中传播速度最快？",
                options: ["A. 空气", "B. 水", "C. 钢铁"],
                correctAnswer: "C",
                explanation: "声音在固体中传播最快，液体次之，气体最慢。钢铁是固体，因此声音在钢铁中传播速度最快。"
            },
            {
                question: "植物的呼吸作用主要发生在？",
                options: ["A. 白天", "B. 晚上", "C. 全天"],
                correctAnswer: "C",
                explanation: "植物的呼吸作用是全天都在进行的，无论是白天还是晚上。呼吸作用为植物提供能量，是植物生命活动的基础。"
            }
        ];

        // 游戏状态变量
        let currentQuestion = 0;
        let score = 0;
        let correctCount = 0;
        let wrongCount = 0;
        let wrongQuestions = [];
        let selectedAnswer = null;
        let currentPage = 1;
        const itemsPerPage = 2;

        // DOM元素
        const welcomeScreen = document.getElementById('welcome-screen');
        const startBtn = document.getElementById('start-btn');
        const questionText = document.getElementById('question-text');
        const options = document.querySelectorAll('.option');
        const levelElement = document.getElementById('level');
        const scoreElement = document.getElementById('score');
        const correctCountElement = document.getElementById('correct-count');
        const wrongCountElement = document.getElementById('wrong-count');
        const nextBtn = document.getElementById('next-btn');
        const wrongList = document.getElementById('wrong-list');
        const questionNum = document.getElementById('question-num');
        const tabs = document.querySelectorAll('.tab');
        const tabContents = document.querySelectorAll('.tab-content');
        const explanationModal = document.getElementById('explanation-modal');
        const explanationText = document.getElementById('explanation-text');
        const closeExplanation = document.getElementById('close-explanation');
        const continueBtn = document.getElementById('continue-btn');
        const resultModal = document.getElementById('result-modal');
        const finalScore = document.getElementById('final-score');
        const finalCorrect = document.getElementById('final-correct');
        const finalWrong = document.getElementById('final-wrong');
        const closeResult = document.getElementById('close-result');
        const restartBtn = document.getElementById('restart-btn');
        const reviewWrongBtn = document.getElementById('review-wrong');
        const prevBtn = document.getElementById('prev-btn');
        const nextPageBtn = document.getElementById('next-page-btn');
        const currentPageSpan = document.getElementById('current-page');
        const pagination = document.getElementById('pagination');
        const aiIcon = document.getElementById('ai-icon');
        const aiChatbox = document.getElementById('ai-chatbox');
        const aiMessages = document.getElementById('ai-messages');
        const aiInput = document.getElementById('ai-input');
        const aiSend = document.getElementById('ai-send');
        const header = document.querySelector('.header');
        const container = document.querySelector('.container');

        // 初始化游戏
        function initGame() {
            currentQuestion = 0;
            score = 0;
            correctCount = 0;
            wrongCount = 0;
            wrongQuestions = [];
            currentPage = 1;
            
            updateStats();
            loadQuestion();
            
            // 更新错题本
            updateWrongBook();
            
            // 切换到答题页面
            showTab('game');
            
            // 显示游戏界面
            header.style.display = 'block';
            container.style.display = 'flex';
        }

        // 开始游戏
        startBtn.addEventListener('click', () => {
            welcomeScreen.style.opacity = '0';
            setTimeout(() => {
                welcomeScreen.style.display = 'none';
                initGame();
            }, 800);
        });

        // 加载问题
        function loadQuestion() {
            const question = scienceQuestions[currentQuestion];
            questionText.textContent = question.question;
            questionNum.textContent = currentQuestion + 1;
            
            options.forEach((option, index) => {
                if (index < question.options.length) {
                    option.textContent = question.options[index];
                    option.dataset.value = String.fromCharCode(65 + index);
                    option.classList.remove('correct', 'wrong');
                    option.style.display = 'block';
                } else {
                    option.style.display = 'none';
                }
            });
            
            nextBtn.disabled = true;
            selectedAnswer = null;
        }

        // 更新状态
        function updateStats() {
            levelElement.textContent = Math.min(Math.floor(currentQuestion / 3) + 1, 4);
            scoreElement.textContent = score;
            correctCountElement.textContent = correctCount;
            wrongCountElement.textContent = wrongCount;
        }

        // 处理选项点击
        options.forEach(option => {
            option.addEventListener('click', () => {
                if (selectedAnswer !== null) return;
                
                selectedAnswer = option.dataset.value;
                const question = scienceQuestions[currentQuestion];
                
                // 标记正确和错误选项
                options.forEach(opt => {
                    if (opt.dataset.value === question.correctAnswer) {
                        opt.classList.add('correct');
                    } else if (opt.dataset.value === selectedAnswer) {
                        opt.classList.add('wrong');
                    }
                });
                
                // 检查答案
                if (selectedAnswer === question.correctAnswer) {
                    score += 10;
                    correctCount++;
                } else {
                    wrongCount++;
                    
                    // 记录错题
                    wrongQuestions.push({
                        question: question.question,
                        options: [...question.options],
                        correctAnswer: question.correctAnswer,
                        explanation: question.explanation,
                        selectedAnswer: selectedAnswer
                    });
                    
                    // 显示知识点解析弹窗
                    explanationText.textContent = question.explanation;
                    explanationModal.style.display = 'flex';
                }
                
                updateStats();
                nextBtn.disabled = false;
            });
        });

        // 下一题
        nextBtn.addEventListener('click', () => {
            currentQuestion++;
            
            if (currentQuestion < scienceQuestions.length) {
                loadQuestion();
            } else {
                // 显示闯关完成弹窗
                finalScore.textContent = score;
                finalCorrect.textContent = correctCount;
                finalWrong.textContent = wrongCount;
                
                // 根据成绩设置不同消息
                const message = score >= 80 ? 
                    "太棒了！你是真正的科学小达人！" : 
                    score >= 60 ? 
                    "做得很好！继续努力成为科学小达人！" : 
                    "不错哦！多复习错题本，下次会更好！";
                
                document.getElementById('result-message').textContent = message;
                
                resultModal.style.display = 'flex';
            }
        });

        // 关闭知识点弹窗
        closeExplanation.addEventListener('click', () => {
            explanationModal.style.display = 'none';
        });
        
        continueBtn.addEventListener('click', () => {
            explanationModal.style.display = 'none';
        });

        // 关闭结果弹窗
        closeResult.addEventListener('click', () => {
            resultModal.style.display = 'none';
        });

        // 重新开始
        restartBtn.addEventListener('click', () => {
            resultModal.style.display = 'none';
            initGame();
        });

        // 查看错题本
        reviewWrongBtn.addEventListener('click', () => {
            resultModal.style.display = 'none';
            showTab('wrong');
        });

        // 更新错题本
        function updateWrongBook() {
            if (wrongQuestions.length === 0) {
                wrongList.innerHTML = `
                    <div class="no-wrong">
                        <i class="fas fa-smile-beam" style="font-size: 3rem; color: #ffd166; margin-bottom: 15px;"></i>
                        <p>目前还没有错题，继续加油！</p>
                    </div>
                `;
                pagination.style.display = 'none';
                return;
            }
            
            // 计算总页数
            const totalPages = Math.ceil(wrongQuestions.length / itemsPerPage);
            
            // 显示分页
            pagination.style.display = totalPages > 1 ? 'flex' : 'none';
            currentPageSpan.textContent = currentPage;
            
            // 更新分页按钮状态
            prevBtn.disabled = currentPage === 1;
            nextPageBtn.disabled = currentPage === totalPages;
            
            // 获取当前页的错题
            const startIndex = (currentPage - 1) * itemsPerPage;
            const endIndex = Math.min(startIndex + itemsPerPage, wrongQuestions.length);
            const currentWrongs = wrongQuestions.slice(startIndex, endIndex);
            
            // 渲染错题
            let html = '';
            currentWrongs.forEach((item, index) => {
                let optionsHTML = '';
                item.options.forEach(opt => {
                    const isCorrect = opt.charAt(0) === item.correctAnswer;
                    const isSelected = opt.charAt(0) === item.selectedAnswer;
                    let optionClass = '';
                    
                    if (isCorrect) {
                        optionClass = 'correct';
                    } else if (isSelected) {
                        optionClass = 'wrong';
                    }
                    
                    optionsHTML += `<div class="wrong-option ${optionClass}">${opt}</div>`;
                });
                
                html += `
                    <div class="wrong-item">
                        <h3>题目 ${startIndex + index + 1}: ${item.question}</h3>
                        <div class="wrong-options">${optionsHTML}</div>
                        <p><strong>解析:</strong> ${item.explanation}</p>
                    </div>
                `;
            });
            
            wrongList.innerHTML = html;
        }

        // 标签切换功能
        tabs.forEach(tab => {
            tab.addEventListener('click', () => {
                const tabName = tab.dataset.tab;
                showTab(tabName);
            });
        });

        function showTab(tabName) {
            // 更新标签状态
            tabs.forEach(tab => {
                if (tab.dataset.tab === tabName) {
                    tab.classList.add('active');
                } else {
                    tab.classList.remove('active');
                }
            });
            
            // 显示对应内容
            tabContents.forEach(content => {
                if (content.id === `${tabName}-tab`) {
                    content.style.display = 'block';
                    
                    // 切换到错题本时更新内容
                    if (tabName === 'wrong') {
                        updateWrongBook();
                    }
                } else {
                    content.style.display = 'none';
                }
            });
        }

        // 分页按钮事件
        prevBtn.addEventListener('click', () => {
            if (currentPage > 1) {
                currentPage--;
                updateWrongBook();
            }
        });

        nextPageBtn.addEventListener('click', () => {
            const totalPages = Math.ceil(wrongQuestions.length / itemsPerPage);
            if (currentPage < totalPages) {
                currentPage++;
                updateWrongBook();
            }
        });

        // AI助手功能
        aiIcon.addEventListener('click', () => {
            aiChatbox.style.display = aiChatbox.style.display === 'flex' ? 'none' : 'flex';
        });

        aiSend.addEventListener('click', sendMessage);
        
        aiInput.addEventListener('keypress', (e) => {
            if (e.key === 'Enter') {
                sendMessage();
            }
        });

        function sendMessage() {
            const message = aiInput.value.trim();
            if (message) {
                // 添加用户消息
                addMessage(message, 'user');
                aiInput.value = '';
                
                // 模拟AI回复
                setTimeout(() => {
                    let response = "我还在学习中，暂时不能回答这个问题。你可以尝试问我关于光、力、植物、动物、水循环等科学知识！";
                    
                    if (message.includes('光') || message.includes('反射') || message.includes('折射')) {
                        response = "光是一种电磁波，可以在真空和透明介质中传播。光遇到物体时可能发生反射、折射或吸收现象。平面镜反射光线，透镜可以折射光线。";
                    } else if (message.includes('力') || message.includes('作用')) {
                        response = "力是物体之间的相互作用，可以改变物体的运动状态或形状。力的单位是牛顿（N）。常见的有重力、摩擦力、弹力等。力的三要素是大小、方向和作用点。";
                    } else if (message.includes('植物') || message.includes('光合')) {
                        response = "植物通过光合作用制造食物。光合作用的公式是：二氧化碳 + 水 → 葡萄糖 + 氧气（在光照和叶绿素作用下）。这个过程主要发生在植物的叶子里。";
                    } else if (message.includes('动物') || message.includes('哺乳')) {
                        response = "动物分为脊椎动物和无脊椎动物。脊椎动物包括鱼类、两栖类、爬行类、鸟类和哺乳类。哺乳动物的特征是体表有毛、胎生、哺乳。";
                    } else if (message.includes('水循环')) {
                        response = "水循环是地球上水从地表蒸发形成水蒸气，上升到高空遇冷凝结成云，再以降水的形式回到地面的过程。主要包括蒸发、凝结、降水和径流四个环节。";
                    }
                    
                    addMessage(response, 'bot');
                }, 1000);
            }
        }

        function addMessage(text, sender) {
            const messageDiv = document.createElement('div');
            messageDiv.classList.add('ai-message', sender);
            messageDiv.textContent = text;
            aiMessages.appendChild(messageDiv);
            aiMessages.scrollTop = aiMessages.scrollHeight;
        }

        // 初始化页面
        window.onload = () => {
            // 修复GitHub渲染问题
            fixGitHubRendering();
            
            // 添加欢迎动画
            document.querySelector('.welcome-title').style.animation = 'popIn 1s forwards';
            document.querySelector('.welcome-subtitle').style.animation = 'popIn 1s 0.3s forwards';
            document.querySelector('.game-instructions').style.animation = 'popIn 1s 0.6s forwards';
            document.querySelector('.start-btn').style.animation = 'popIn 1s 0.9s forwards';
        };
    </script>
</body>
</html>
