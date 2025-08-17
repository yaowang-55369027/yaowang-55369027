<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>科学小达人 - 五年级科学闯关答题</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Ma+Shan+Zheng&display=swap" rel="stylesheet">
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
        
        /* 欢迎界面 */
        .welcome-screen {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://images.unsplash.com/photo-1532094349884-543bc11b234d?ixlib=rb-4.0.3&auto=format&fit=crop&w=1920&q=80') no-repeat center center;
            background-size: cover;
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
            font-family: 'Ma Shan Zheng', cursive;
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
            opacity: 0;
            transform: translateY(20px);
            animation: fadeInUp 0.8s 0.3s forwards;
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
            opacity: 0;
            transform: translateY(20px);
            animation: fadeInUp 0.8s 0.5s forwards;
        }
        
        @keyframes fadeInUp {
            to {
                opacity: 1;
                transform: translateY(0);
            }
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
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .ai-messages {
            height: 300px;
            padding: 15px;
            overflow-y: auto;
            background: #f9f9f9;
            display: flex;
            flex-direction: column;
            gap: 12px;
        }
        
        .ai-message {
            padding: 12px 16px;
            border-radius: 15px;
            max-width: 85%;
            line-height: 1.5;
            position: relative;
            animation: messageAppear 0.3s ease-out;
        }
        
        @keyframes messageAppear {
            0% { opacity: 0; transform: translateY(10px); }
            100% { opacity: 1; transform: translateY(0); }
        }
        
        .ai-message.bot {
            background: #e6f7ff;
            align-self: flex-start;
            border-bottom-left-radius: 5px;
        }
        
        .ai-message.bot:before {
            content: "";
            position: absolute;
            left: -10px;
            top: 10px;
            width: 0;
            height: 0;
            border-top: 10px solid transparent;
            border-bottom: 10px solid transparent;
            border-right: 10px solid #e6f7ff;
        }
        
        .ai-message.user {
            background: #d1e8ff;
            align-self: flex-end;
            border-bottom-right-radius: 5px;
        }
        
        .ai-message.user:after {
            content: "";
            position: absolute;
            right: -10px;
            top: 10px;
            width: 0;
            height: 0;
            border-top: 10px solid transparent;
            border-bottom: 10px solid transparent;
            border-left: 10px solid #d1e8ff;
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
        
        .ai-typing {
            display: flex;
            align-items: center;
            padding: 8px 15px;
            background: #e6f7ff;
            border-radius: 15px;
            width: fit-content;
            margin-top: 5px;
        }
        
        .ai-typing span {
            height: 8px;
            width: 8px;
            border-radius: 50%;
            background: #4facfe;
            display: inline-block;
            margin: 0 2px;
            animation: typing 1s infinite;
        }
        
        .ai-typing span:nth-child(2) {
            animation-delay: 0.2s;
        }
        
        .ai-typing span:nth-child(3) {
            animation-delay: 0.4s;
        }
        
        @keyframes typing {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-5px); }
        }
        
        .ai-close {
            background: none;
            border: none;
            color: white;
            cursor: pointer;
            font-size: 1.2rem;
        }
        
        .ai-mode {
            background: rgba(255, 255, 255, 0.2);
            padding: 3px 10px;
            border-radius: 15px;
            font-size: 0.8rem;
        }
        
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
                <div>
                    <i class="fas fa-robot"></i> 科学小助手
                    <span class="ai-mode">智能模式</span>
                </div>
                <button class="ai-close" id="ai-close">
                    <i class="fas fa-times"></i>
                </button>
            </div>
            <div class="ai-messages" id="ai-messages">
                <div class="ai-message bot">
                    你好！我是你的科学小助手，可以回答各种科学问题。<br><br>
                    你可以问我关于：
                    <ul>
                        <li>物理现象（光、力、声音等）</li>
                        <li>生物知识（植物、动物、人体等）</li>
                        <li>地球科学（天气、水循环、岩石等）</li>
                        <li>化学常识（物质变化、元素等）</li>
                    </ul>
                    试试问我："什么是光合作用？" 或 "声音是如何传播的？"
                </div>
            </div>
            <div class="ai-input">
                <input type="text" id="ai-input" placeholder="输入科学问题...">
                <button id="ai-send"><i class="fas fa-paper-plane"></i></button>
            </div>
        </div>
    </div>

    <script>
        // 科学题库（100道题）
        const scienceQuestions = [
            // 物理类题目
            {
                question: "当光线照射到平面镜上时，会发生什么现象？",
                options: ["A. 折射", "B. 反射", "C. 透射"],
                correctAnswer: "B",
                explanation: "当光线照射到平面镜上时，会发生反射现象。反射是指光线在遇到光滑表面时，按照入射角等于反射角的规律返回的现象。平面镜是典型的反射面，能够将光线反射回去。"
            },
            {
                question: "声音在下列哪种介质中传播速度最快？",
                options: ["A. 空气", "B. 水", "C. 钢铁"],
                correctAnswer: "C",
                explanation: "声音在固体中传播最快，液体次之，气体最慢。钢铁是固体，因此声音在钢铁中传播速度最快。"
            },
            {
                question: "下列哪种物质是绝缘体？",
                options: ["A. 铜", "B. 铁", "C. 橡胶"],
                correctAnswer: "C",
                explanation: "橡胶是绝缘体，不容易导电。而铜、铁是导体，容易导电。绝缘体在电路中用于防止电流流向不需要的地方，保证用电安全。"
            },
            {
                question: "下列哪种简单机械利用了杠杆原理？",
                options: ["A. 滑轮", "B. 螺丝刀", "C. 斜面"],
                correctAnswer: "B",
                explanation: "螺丝刀利用了杠杆原理，通过手柄施加较小的力，在刀口处产生较大的力，从而轻松拧动螺丝。"
            },
            {
                question: "下列哪种现象是由于光的折射造成的？",
                options: ["A. 彩虹", "B. 镜子成像", "C. 树荫"],
                correctAnswer: "A",
                explanation: "彩虹是由于光的折射和反射形成的。当阳光穿过雨滴时，会发生折射、反射和再次折射，将白光分解成七种颜色。"
            },
            {
                question: "磁铁的两极分别叫做什么？",
                options: ["A. 东极和西极", "B. 南极和北极", "C. 正极和负极"],
                correctAnswer: "B",
                explanation: "磁铁的两极分别叫做南极(S极)和北极(N极)。同名磁极相互排斥，异名磁极相互吸引。"
            },
            {
                question: "水在什么温度下会沸腾？",
                options: ["A. 90°C", "B. 100°C", "C. 110°C"],
                correctAnswer: "B",
                explanation: "在标准大气压下，水的沸点是100°C。当水加热到这个温度时，水会从液态转变为气态，产生大量气泡。"
            },
            {
                question: "下列哪种能量转换发生在电风扇中？",
                options: ["A. 电能→光能", "B. 电能→动能", "C. 动能→电能"],
                correctAnswer: "B",
                explanation: "电风扇工作时，电能被转换为电动机的动能，使扇叶旋转产生风。"
            },
            {
                question: "下列哪种现象是由于地球自转引起的？",
                options: ["A. 四季变化", "B. 昼夜交替", "C. 月相变化"],
                correctAnswer: "B",
                explanation: "地球绕地轴自转一周约24小时，造成太阳照射地球的不同区域，形成了昼夜交替的现象。"
            },
            {
                question: "下列哪种现象是摩擦力的作用？",
                options: ["A. 滑冰", "B. 写字", "C. 游泳"],
                correctAnswer: "B",
                explanation: "写字时，笔尖与纸张之间的摩擦力使墨水能够留在纸上形成字迹。没有摩擦力，笔尖会在纸上打滑。"
            },
            
            // 生物类题目
            {
                question: "植物进行光合作用的主要场所是哪里？",
                options: ["A. 根", "B. 茎", "C. 叶"],
                correctAnswer: "C",
                explanation: "植物进行光合作用的主要场所是叶。叶中含有叶绿体，叶绿体是光合作用的场所，能够利用光能将二氧化碳和水转化为有机物，并释放氧气。"
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
                question: "植物的呼吸作用主要发生在？",
                options: ["A. 白天", "B. 晚上", "C. 全天"],
                correctAnswer: "C",
                explanation: "植物的呼吸作用是全天都在进行的，无论是白天还是晚上。呼吸作用为植物提供能量，是植物生命活动的基础。"
            },
            {
                question: "下列哪项不是昆虫的特征？",
                options: ["A. 三对足", "B. 两对翅膀", "C. 有脊椎"],
                correctAnswer: "C",
                explanation: "昆虫是无脊椎动物，它们有三对足，通常有两对翅膀（但有些昆虫可能只有一对翅膀或没有翅膀）。"
            },
            {
                question: "下列哪种植物属于裸子植物？",
                options: ["A. 松树", "B. 苹果树", "C. 水稻"],
                correctAnswer: "A",
                explanation: "松树属于裸子植物，它们的种子裸露在外，没有果实包裹。苹果树和水稻属于被子植物，种子包裹在果实内。"
            },
            {
                question: "下列哪项是细胞的基本功能？",
                options: ["A. 呼吸", "B. 繁殖", "C. 以上都是"],
                correctAnswer: "C",
                explanation: "细胞是生物体的基本结构和功能单位，具有呼吸、繁殖、营养摄取等多种基本功能。"
            },
            {
                question: "下列哪种物质是植物光合作用的产物？",
                options: ["A. 二氧化碳", "B. 氧气", "C. 水"],
                correctAnswer: "B",
                explanation: "植物光合作用的产物是葡萄糖和氧气。光合作用利用二氧化碳和水，在光照条件下产生葡萄糖并释放氧气。"
            },
            {
                question: "人体最大的器官是什么？",
                options: ["A. 肝脏", "B. 皮肤", "C. 肺"],
                correctAnswer: "B",
                explanation: "皮肤是人体最大的器官，覆盖全身表面，具有保护、感觉、调节体温等多种功能。"
            },
            {
                question: "下列哪种动物是肉食动物？",
                options: ["A. 兔子", "B. 狮子", "C. 牛"],
                correctAnswer: "B",
                explanation: "狮子是肉食动物，主要以其他动物为食。兔子和牛是草食动物，以植物为食。"
            },
            
            // 地球科学类题目
            {
                question: "水在自然界中的循环过程不包括以下哪个环节？",
                options: ["A. 蒸发", "B. 光合作用", "C. 降水"],
                correctAnswer: "B",
                explanation: "水循环的主要过程包括蒸发（水变成水蒸气）、凝结（水蒸气变成小水滴）、降水（雨、雪等）以及径流等环节。光合作用是植物制造有机物的过程，不属于水循环环节。"
            },
            {
                question: "下列能源中，属于可再生能源的是？",
                options: ["A. 煤炭", "B. 石油", "C. 太阳能"],
                correctAnswer: "C",
                explanation: "太阳能是可再生能源，可以持续利用。煤炭、石油是化石能源，形成需要数百万年，属于不可再生能源。"
            },
            {
                question: "下列哪种岩石属于沉积岩？",
                options: ["A. 花岗岩", "B. 大理石", "C. 砂岩"],
                correctAnswer: "C",
                explanation: "砂岩属于沉积岩，由沙粒经过长时间压实和胶结形成。花岗岩是火成岩，大理石是变质岩。"
            },
            {
                question: "下列哪种天气现象通常伴随着强冷空气南下？",
                options: ["A. 台风", "B. 寒潮", "C. 梅雨"],
                correctAnswer: "B",
                explanation: "寒潮是强冷空气南下造成的剧烈降温天气现象，通常伴有大风和雨雪天气。"
            },
            {
                question: "地球内部结构由外到内依次是？",
                options: ["A. 地核-地幔-地壳", "B. 地壳-地幔-地核", "C. 地幔-地核-地壳"],
                correctAnswer: "B",
                explanation: "地球内部结构由外到内依次是地壳、地幔和地核。地壳最薄，地核温度最高。"
            },
            {
                question: "下列哪项不是保护环境的行为？",
                options: ["A. 垃圾分类", "B. 使用一次性塑料袋", "C. 植树造林"],
                correctAnswer: "B",
                explanation: "使用一次性塑料袋会增加白色污染，不利于环境保护。垃圾分类和植树造林都是保护环境的行为。"
            },
            {
                question: "下列哪种资源属于不可再生资源？",
                options: ["A. 风能", "B. 煤炭", "C. 太阳能"],
                correctAnswer: "B",
                explanation: "煤炭属于不可再生资源，形成需要数百万年时间。风能和太阳能是可再生资源，可以持续利用。"
            },
            {
                question: "造成酸雨的主要污染物是什么？",
                options: ["A. 二氧化碳", "B. 二氧化硫", "C. 氧气"],
                correctAnswer: "B",
                explanation: "二氧化硫是造成酸雨的主要污染物之一，它在大气中与水蒸气反应形成硫酸，随雨水降落到地面形成酸雨。"
            },
            {
                question: "下列哪项不是水污染的主要来源？",
                options: ["A. 工业废水", "B. 生活污水", "C. 植树造林"],
                correctAnswer: "C",
                explanation: "植树造林有助于保护水源，防止水土流失，不是水污染源。工业废水和生活污水是水污染的主要来源。"
            },
            {
                question: "下列哪项是风能利用的方式？",
                options: ["A. 火力发电", "B. 风力发电", "C. 核能发电"],
                correctAnswer: "B",
                explanation: "风力发电是利用风的动能驱动风力发电机叶片旋转，从而产生电能的清洁能源利用方式。"
            },
            
            // 化学类题目
            {
                question: "下列哪种变化属于物理变化？",
                options: ["A. 铁生锈", "B. 水结冰", "C. 食物腐烂"],
                correctAnswer: "B",
                explanation: "水结冰是物理变化，只是物质状态改变，没有新物质生成。铁生锈和食物腐烂是化学变化，有新物质生成。"
            },
            {
                question: "下列哪种气体能使澄清石灰水变浑浊？",
                options: ["A. 氧气", "B. 二氧化碳", "C. 氮气"],
                correctAnswer: "B",
                explanation: "二氧化碳能使澄清石灰水变浑浊，这是检验二氧化碳的方法之一。"
            },
            {
                question: "下列哪种物质是酸性物质？",
                options: ["A. 柠檬汁", "B. 肥皂水", "C. 小苏打溶液"],
                correctAnswer: "A",
                explanation: "柠檬汁含有柠檬酸，呈酸性。肥皂水和小苏打溶液呈碱性。"
            },
            {
                question: "下列哪项是燃烧的必要条件？",
                options: ["A. 可燃物", "B. 氧气", "C. 以上都是"],
                correctAnswer: "C",
                explanation: "燃烧需要三个必要条件：可燃物、氧气（或助燃物）和达到着火点的温度。"
            },
            {
                question: "下列哪种物质是纯净物？",
                options: ["A. 空气", "B. 蒸馏水", "C. 牛奶"],
                correctAnswer: "B",
                explanation: "蒸馏水是纯净物，只含有水分子。空气是混合物，含有氮气、氧气等多种气体；牛奶也是混合物。"
            },
            {
                question: "下列哪项不是金属的特性？",
                options: ["A. 导电性", "B. 延展性", "C. 易碎性"],
                correctAnswer: "C",
                explanation: "金属通常具有导电性、导热性、延展性和金属光泽。易碎性不是金属的普遍特性，许多金属具有韧性。"
            },
            {
                question: "下列哪种方法可以加快糖在水中的溶解速度？",
                options: ["A. 加热", "B. 搅拌", "C. 以上都是"],
                correctAnswer: "C",
                explanation: "加热和搅拌都可以加快糖在水中的溶解速度。加热增加了分子运动速度，搅拌使糖分子更快分散。"
            },
            {
                question: "下列哪项是防止铁生锈的方法？",
                options: ["A. 涂油漆", "B. 保持干燥", "C. 以上都是"],
                correctAnswer: "C",
                explanation: "涂油漆可以隔绝铁与氧气和水的接触，保持干燥可以减少水的影响，都是防止铁生锈的有效方法。"
            },
            {
                question: "下列哪种物质能导电？",
                options: ["A. 纯净水", "B. 食盐水", "C. 糖水"],
                correctAnswer: "B",
                explanation: "食盐水能导电，因为其中含有可以自由移动的离子。纯净水和糖水几乎没有自由移动的离子，不导电。"
            },
            {
                question: "下列哪项是化学变化的特征？",
                options: ["A. 状态改变", "B. 产生新物质", "C. 形状改变"],
                correctAnswer: "B",
                explanation: "化学变化的本质特征是有新物质生成。状态改变和形状改变可能是物理变化。"
            },
            
            // 更多题目
            {
                question: "下列哪种器官属于消化系统？",
                options: ["A. 心脏", "B. 肺", "C. 胃"],
                correctAnswer: "C",
                explanation: "胃属于消化系统，负责食物的初步消化。心脏属于循环系统，肺属于呼吸系统。"
            },
            {
                question: "下列哪项是哺乳动物的特征？",
                options: ["A. 卵生", "B. 有羽毛", "C. 用乳汁哺育幼崽"],
                correctAnswer: "C",
                explanation: "哺乳动物的主要特征包括胎生（除鸭嘴兽等少数例外）、体表有毛发、用乳汁哺育幼崽。"
            },
            {
                question: "下列哪种气体是植物光合作用需要的？",
                options: ["A. 氧气", "B. 二氧化碳", "C. 氮气"],
                correctAnswer: "B",
                explanation: "植物光合作用需要二氧化碳作为原料，在光照条件下与水反应生成葡萄糖和氧气。"
            },
            {
                question: "下列哪项不是节约用水的行为？",
                options: ["A. 用淘米水浇花", "B. 长时间淋浴", "C. 使用节水马桶"],
                correctAnswer: "B",
                explanation: "长时间淋浴会浪费大量水资源，不是节约用水的行为。用淘米水浇花和用节水马桶都是节约用水的行为。"
            },
            {
                question: "下列哪种动物是草食动物？",
                options: ["A. 老虎", "B. 大象", "C. 老鹰"],
                correctAnswer: "B",
                explanation: "大象是草食动物，主要以植物为食。老虎和老鹰是肉食动物。"
            },
            {
                question: "下列哪项是保护生物多样性的意义？",
                options: ["A. 维持生态平衡", "B. 提供更多资源", "C. 以上都是"],
                correctAnswer: "C",
                explanation: "保护生物多样性有助于维持生态平衡，为人类提供食物、药物等多种资源，对地球生态系统至关重要。"
            },
            {
                question: "下列哪项不是影响植物生长的因素？",
                options: ["A. 阳光", "B. 水", "C. 电视"],
                correctAnswer: "C",
                explanation: "电视不会影响植物生长。植物生长需要阳光、水、空气、适宜的温度和养分等条件。"
            },
            {
                question: "下列哪种现象是由于地球公转引起的？",
                options: ["A. 昼夜交替", "B. 四季变化", "C. 月相变化"],
                correctAnswer: "B",
                explanation: "地球绕太阳公转时，由于地轴倾斜，造成不同季节太阳直射点在地球上的位置变化，形成四季。"
            },
            {
                question: "下列哪项是安全用电的做法？",
                options: ["A. 湿手触摸电器", "B. 使用绝缘破损的电线", "C. 不用时要关闭电源"],
                correctAnswer: "C",
                explanation: "不用时关闭电源是安全用电的做法。湿手触摸电器和使用绝缘破损的电线都是危险行为。"
            },
            {
                question: "下列哪种物质可以溶解在水中？",
                options: ["A. 食用油", "B. 食盐", "C. 沙子"],
                correctAnswer: "B",
                explanation: "食盐可以溶解在水中形成溶液。食用油和沙子不溶于水，会形成混合物。"
            },
            
            // 继续添加题目
            {
                question: "下列哪种感觉器官负责嗅觉？",
                options: ["A. 眼睛", "B. 鼻子", "C. 耳朵"],
                correctAnswer: "B",
                explanation: "鼻子是负责嗅觉的感觉器官，能感知气味分子。眼睛负责视觉，耳朵负责听觉。"
            },
            {
                question: "下列哪项不是昆虫的特征？",
                options: ["A. 身体分为头、胸、腹三部分", "B. 有六条腿", "C. 有脊椎"],
                correctAnswer: "C",
                explanation: "昆虫是无脊椎动物，没有脊椎。它们的身体分为头、胸、腹三部分，通常有六条腿。"
            },
            {
                question: "下列哪种天气现象通常出现在夏季？",
                options: ["A. 下雪", "B. 雷电", "C. 结霜"],
                correctAnswer: "B",
                explanation: "雷电通常出现在夏季，因为夏季气温高，空气对流强烈，容易形成雷雨云。"
            },
            {
                question: "下列哪种能源属于化石能源？",
                options: ["A. 风能", "B. 太阳能", "C. 天然气"],
                correctAnswer: "C",
                explanation: "天然气属于化石能源，是古代生物遗骸经过长时间地质作用形成的。风能和太阳能是可再生能源。"
            },
            {
                question: "下列哪项是减少空气污染的方法？",
                options: ["A. 多开私家车", "B. 植树造林", "C. 焚烧垃圾"],
                correctAnswer: "B",
                explanation: "植树造林有助于吸收二氧化碳，释放氧气，减少空气污染。多开私家车和焚烧垃圾会增加空气污染。"
            },
            {
                question: "下列哪种动物是两栖动物？",
                options: ["A. 青蛙", "B. 乌龟", "C. 鳄鱼"],
                correctAnswer: "A",
                explanation: "青蛙是两栖动物，既能在水中生活，也能在陆地上生活。乌龟和鳄鱼是爬行动物。"
            },
            {
                question: "下列哪项是健康饮食的原则？",
                options: ["A. 食物多样化", "B. 多吃蔬菜水果", "C. 以上都是"],
                correctAnswer: "C",
                explanation: "健康饮食的原则包括食物多样化、多吃蔬菜水果、适量摄入各类营养素、控制油盐糖的摄入等。"
            },
            {
                question: "下列哪种物质是固体？",
                options: ["A. 空气", "B. 水", "C. 冰块"],
                correctAnswer: "C",
                explanation: "冰块是水的固态形式，属于固体。空气是气体，水是液体。"
            },
            {
                question: "下列哪项是地球的天然卫星？",
                options: ["A. 太阳", "B. 月球", "C. 火星"],
                correctAnswer: "B",
                explanation: "月球是地球唯一的天然卫星，围绕地球公转。太阳是恒星，火星是行星。"
            },
            {
                question: "下列哪种材料最适合制作炒锅的锅柄？",
                options: ["A. 铁", "B. 塑料", "C. 木材"],
                correctAnswer: "C",
                explanation: "木材是热的不良导体，适合制作锅柄，使用时不会烫手。铁和塑料（某些类型）导热性好，容易烫手。"
            },
            
            // 最后20道题
            {
                question: "下列哪种动物是恒温动物？",
                options: ["A. 蛇", "B. 鸟", "C. 鱼"],
                correctAnswer: "B",
                explanation: "鸟类是恒温动物，能保持体温恒定。蛇和鱼是变温动物，体温随环境变化。"
            },
            {
                question: "下列哪项不是植物传播种子的方式？",
                options: ["A. 风力传播", "B. 动物传播", "C. 电话传播"],
                correctAnswer: "C",
                explanation: "植物传播种子的方式包括风力传播、动物传播、水力传播和弹射传播等，没有电话传播。"
            },
            {
                question: "下列哪项是预防传染病的方法？",
                options: ["A. 勤洗手", "B. 接种疫苗", "C. 以上都是"],
                correctAnswer: "C",
                explanation: "预防传染病的方法包括勤洗手、接种疫苗、保持环境卫生、避免接触传染源等。"
            },
            {
                question: "下列哪种现象是由于水的表面张力造成的？",
                options: ["A. 水往低处流", "B. 水滴呈球形", "C. 冰浮在水面上"],
                correctAnswer: "B",
                explanation: "水滴呈球形是由于水的表面张力作用，使水滴表面积尽可能缩小。"
            },
            {
                question: "下列哪项是月球对地球的影响？",
                options: ["A. 引起潮汐", "B. 产生四季", "C. 造成昼夜交替"],
                correctAnswer: "A",
                explanation: "月球引力是引起地球潮汐现象的主要原因。四季是由于地球公转和地轴倾斜造成的，昼夜交替是由于地球自转造成的。"
            },
            {
                question: "下列哪种方法可以分离沙子和盐的混合物？",
                options: ["A. 磁铁吸引", "B. 溶解过滤", "C. 直接加热"],
                correctAnswer: "B",
                explanation: "分离沙子和盐的混合物可以先将混合物溶解在水中，盐溶解而沙子不溶，过滤分离出沙子，再将盐水蒸发得到盐。"
            },
            {
                question: "下列哪项是人体最大的消化腺？",
                options: ["A. 胃", "B. 肝脏", "C. 胰腺"],
                correctAnswer: "B",
                explanation: "肝脏是人体最大的消化腺，分泌胆汁帮助消化脂肪，同时还具有解毒、储存营养等多种功能。"
            },
            {
                question: "下列哪项不是生态系统中的生产者？",
                options: ["A. 草", "B. 树", "C. 狮子"],
                correctAnswer: "C",
                explanation: "狮子是消费者，不是生产者。草和树是生产者，能通过光合作用制造有机物。"
            },
            {
                question: "下列哪种现象是静电作用？",
                options: ["A. 磁铁吸铁", "B. 梳子吸小纸片", "C. 水流向下"],
                correctAnswer: "B",
                explanation: "梳子梳头后会产生静电，能吸引小纸片。磁铁吸铁是磁力作用，水流向下是重力作用。"
            },
            {
                question: "下列哪项是正确使用温度计的方法？",
                options: ["A. 测量时接触容器底", "B. 读数时视线与液柱持平", "C. 测量高温液体后立即用冷水冲洗"],
                correctAnswer: "B",
                explanation: "使用温度计时，读数时视线应与液柱上表面持平。不应接触容器底，测量高温液体后应自然冷却，避免骤冷导致破裂。"
            },
            {
                question: "下列哪项是环境保护的'3R'原则？",
                options: ["A. 减少、重复使用、回收", "B. 阅读、写作、算术", "C. 跑步、跳跃、投掷"],
                correctAnswer: "A",
                explanation: "环境保护的'3R'原则是减少(Reduce)、重复使用(Reuse)、回收(Recycle)，旨在减少资源消耗和环境污染。"
            },
            {
                question: "下列哪种动物有再生能力？",
                options: ["A. 蚯蚓", "B. 壁虎", "C. 以上都是"],
                correctAnswer: "C",
                explanation: "蚯蚓被切断后能再生出缺失部分，壁虎尾巴断裂后能再生，它们都具有再生能力。"
            },
            {
                question: "下列哪项是防止水土流失的方法？",
                options: ["A. 植树造林", "B. 修建梯田", "C. 以上都是"],
                correctAnswer: "C",
                explanation: "植树造林和修建梯田都是防止水土流失的有效方法。植物根系能固定土壤，梯田能减缓水流速度。"
            },
            {
                question: "下列哪种物质是酸和碱中和反应的产物？",
                options: ["A. 盐和水", "B. 酸和碱", "C. 气体"],
                correctAnswer: "A",
                explanation: "酸和碱发生中和反应生成盐和水，这是中和反应的特征。"
            },
            {
                question: "下列哪项是心脏的功能？",
                options: ["A. 消化食物", "B. 泵送血液", "C. 过滤废物"],
                correctAnswer: "B",
                explanation: "心脏的主要功能是泵送血液，使血液在全身循环。消化食物是消化系统的功能，过滤废物是肾脏的功能。"
            },
            {
                question: "下列哪项不是影响蒸发速度的因素？",
                options: ["A. 温度", "B. 表面积", "C. 水的颜色"],
                correctAnswer: "C",
                explanation: "水的颜色不会影响蒸发速度。蒸发速度受温度、表面积、空气湿度和空气流动速度等因素影响。"
            },
            {
                question: "下列哪种物质是单质？",
                options: ["A. 水", "B. 氧气", "C. 食盐"],
                correctAnswer: "B",
                explanation: "氧气是由同种元素组成的纯净物，属于单质。水和食盐是化合物。"
            },
            {
                question: "下列哪项是食物链的正确表示？",
                options: ["A. 草→兔→鹰", "B. 鹰→兔→草", "C. 兔→草→鹰"],
                correctAnswer: "A",
                explanation: "食物链表示生物之间的食物关系，通常从生产者开始，然后是消费者。草是生产者，兔是初级消费者，鹰是次级消费者。"
            },
            {
                question: "下列哪种现象是由于地球引力造成的？",
                options: ["A. 苹果落地", "B. 水往低处流", "C. 以上都是"],
                correctAnswer: "C",
                explanation: "地球引力使物体具有重量，导致苹果落地和水往低处流等现象。"
            },
            {
                question: "下列哪项是正确使用显微镜的步骤？",
                options: ["A. 先高倍后低倍", "B. 眼睛贴近目镜", "C. 转动粗准焦螺旋缓慢下降镜筒"],
                correctAnswer: "C",
                explanation: "使用显微镜时，应先低倍后高倍观察，眼睛不要贴近目镜，转动粗准焦螺旋时应缓慢下降镜筒，避免压碎玻片。"
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
        let currentQuestions = [];

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
        const aiClose = document.getElementById('ai-close');

        // 初始化游戏
        function initGame() {
            // 随机抽取10道题
            currentQuestions = getRandomQuestions(10);
            
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
        }

        // 获取随机题目
        function getRandomQuestions(count) {
            const shuffled = [...scienceQuestions].sort(() => 0.5 - Math.random());
            return shuffled.slice(0, count);
        }

        // 开始游戏
        startBtn.addEventListener('click', () => {
            welcomeScreen.style.opacity = '0';
            setTimeout(() => {
                welcomeScreen.style.display = 'none';
                document.querySelector('.header').style.display = 'block';
                document.querySelector('.container').style.display = 'flex';
            }, 800);
            
            initGame();
        });

        // 加载问题
        function loadQuestion() {
            const question = currentQuestions[currentQuestion];
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
                const question = currentQuestions[currentQuestion];
                
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
            
            if (currentQuestion < currentQuestions.length) {
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
            if (aiChatbox.style.display === 'flex') {
                aiInput.focus();
            }
        });

        aiClose.addEventListener('click', () => {
            aiChatbox.style.display = 'none';
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
                
                // 显示正在输入状态
                const typingIndicator = document.createElement('div');
                typingIndicator.className = 'ai-typing';
                typingIndicator.innerHTML = '<span></span><span></span><span></span>';
                aiMessages.appendChild(typingIndicator);
                aiMessages.scrollTop = aiMessages.scrollHeight;
                
                // 模拟AI回复（实际应用中应连接后端API）
                setTimeout(() => {
                    aiMessages.removeChild(typingIndicator);
                    
                    // 智能回复
                    let response = getAIResponse(message);
                    
                    addMessage(response, 'bot');
                }, 1500);
            }
        }
        
        function getAIResponse(message) {
            // 科学知识库
            const knowledgeBase = {
                "光合作用": "光合作用是植物利用光能将二氧化碳和水转化为葡萄糖和氧气的过程。反应式：6CO₂ + 6H₂O → C₆H₁₂O₆ + 6O₂。这个过程在叶绿体中进行，是地球上最重要的化学反应之一。",
                "反射折射": "光的反射是光线遇到物体表面时改变方向返回的现象，遵循反射定律：入射角等于反射角。光的折射是光线从一种介质进入另一种介质时改变方向的现象，遵循折射定律（斯涅尔定律）。",
                "水循环": "水循环是地球上的水在太阳辐射和重力作用下不断运动的过程。主要环节包括：蒸发、凝结、降水、径流。水循环维持了地球上的水平衡和生态系统。",
                "食物链": "食物链是生物之间吃与被吃的关系链。例如：草→兔→狐狸。食物链通常从生产者（植物）开始，然后是初级消费者（食草动物）、次级消费者（食肉动物）。多条食物链构成食物网。",
                "地球结构": "地球内部结构分为三层：地壳（最外层，平均厚度35公里）、地幔（中间层，约2900公里厚）、地核（最内层，分为液态外核和固态内核）。地壳主要由岩石组成，地核主要由铁和镍组成。",
                "生态系统": "生态系统是生物群落与其环境相互作用形成的统一整体。包括生物成分（生产者、消费者、分解者）和非生物成分（水、土壤、空气等）。生态系统具有能量流动和物质循环的功能。",
                "磁铁": "磁铁具有南北两极，同名极相斥，异名极相吸。地球本身是一个巨大的磁体，有地磁场。磁铁能吸引铁、镍、钴等磁性材料。磁铁在生活中的应用包括指南针、电动机、磁悬浮列车等。",
                "浮力": "浮力是物体在流体中受到的向上托起的力，大小等于物体排开流体的重量（阿基米德原理）。浮力使船能浮在水面上，热气球能升空。物体沉浮取决于自身密度与流体密度的比较。",
                "月相": "月相是月球被太阳照亮部分在地球上呈现的不同形状。月相变化周期约29.5天，包括新月、上弦月、满月、下弦月等阶段。月相变化是由于月球绕地球公转时，日地月三者位置变化造成的。",
                "天气": "天气是指某地区短时间内的大气状况，包括温度、湿度、降水、风、云量等。天气预报主要依据气象卫星、雷达、地面观测站等数据。主要天气现象有晴、阴、雨、雪、风、雾等。"
            };
            
            // 关键词匹配
            const keywords = {
                "光合作用": "光合作用",
                "光合作": "光合作用",
                "植物如何制造食物": "光合作用",
                "反射": "反射折射",
                "折射": "反射折射",
                "光线": "反射折射",
                "水循环": "水循环",
                "水循": "水循环",
                "食物链": "食物链",
                "食物网": "食物链",
                "地球结构": "地球结构",
                "地壳": "地球结构",
                "地核": "地球结构",
                "生态系统": "生态系统",
                "生态": "生态系统",
                "磁铁": "磁铁",
                "磁力": "磁铁",
                "磁极": "磁铁",
                "浮力": "浮力",
                "沉浮": "浮力",
                "月相": "月相",
                "月亮": "月相",
                "天气": "天气",
                "气候": "天气"
            };
            
            // 查找匹配的关键词
            let response = "我还在学习中，暂时不能回答这个问题。你可以问我关于：物理现象（光、力、声音等）、生物知识（植物、动物、人体等）、地球科学（天气、水循环、岩石等）、化学常识（物质变化、元素等）。";
            
            for (const [key, value] of Object.entries(keywords)) {
                if (message.toLowerCase().includes(key.toLowerCase())) {
                    response = knowledgeBase[value];
                    break;
                }
            }
            
            // 特殊问题处理
            if (message.includes("什么是科学") || message.includes("科学是什么")) {
                response = "科学是研究自然现象及其规律的知识体系。它包括观察、提问、假设、实验、分析和得出结论的过程。科学帮助我们理解世界，解决问题，并推动技术进步。";
            }
            else if (message.includes("如何保护环境")) {
                response = "保护环境的方法包括：1. 节约用水用电 2. 垃圾分类回收 3. 减少使用一次性塑料 4. 多步行或骑自行车 5. 植树造林 6. 保护野生动植物。每个人都能为环保贡献力量！";
            }
            else if (message.includes("地球年龄")) {
                response = "地球的年龄约45.4亿年。科学家通过测量岩石中的放射性同位素（如铀铅测年法）来确定地球的年龄。";
            }
            
            return response;
        }

        function addMessage(text, sender) {
            const messageDiv = document.createElement('div');
            messageDiv.classList.add('ai-message', sender);
            messageDiv.textContent = text;
            aiMessages.appendChild(messageDiv);
            aiMessages.scrollTop = aiMessages.scrollHeight;
        }

        // 初始化游戏
        window.onload = () => {
            // 添加欢迎动画
            document.querySelector('.welcome-title').style.animation = 'fadeInUp 1s forwards';
            document.querySelector('.welcome-subtitle').style.animation = 'fadeInUp 1s 0.3s forwards';
            document.querySelector('.game-instructions').style.animation = 'fadeInUp 1s 0.6s forwards';
            document.querySelector('.start-btn').style.animation = 'fadeInUp 1s 0.9s forwards';
        };
    </script>
</body>
</html>
