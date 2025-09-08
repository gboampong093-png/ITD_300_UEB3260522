<?php
// Handle form submission
if ($_SERVER['REQUEST_METHOD'] === 'POST') {
    $subject = $_POST['subject'] ?? '';
    $task = $_POST['task'] ?? '';
    $due_date = $_POST['due_date'] ?? '';
    
    // Basic validation
    if (!empty($subject) && !empty($task) && !empty($due_date)) {
        // In a real application, you would save to a database here
        // For this example, we'll just store in session
        session_start();
        $_SESSION['tasks'][] = [
            'subject' => htmlspecialchars($subject),
            'task' => htmlspecialchars($task),
            'due_date' => htmlspecialchars($due_date)
        ];
    }
}

// Get existing tasks
session_start();
$tasks = $_SESSION['tasks'] ?? [];
?>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Study Planner</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
        }
        
        .container {
            width: 100%;
            max-width: 800px;
            display: flex;
            flex-direction: column;
            gap: 30px;
        }
        
        .planner-card {
            background: white;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            padding: 30px;
        }
        
        h1 {
            color: #2c3e50;
            text-align: center;
            margin-bottom: 25px;
            font-weight: 600;
        }
        
        .form-group {
            margin-bottom: 20px;
        }
        
        label {
            display: block;
            margin-bottom: 8px;
            font-weight: 500;
            color: #34495e;
        }
        
        input, textarea {
            width: 100%;
            padding: 12px 15px;
            border: 1px solid #ddd;
            border-radius: 8px;
            font-size: 16px;
            transition: border-color 0.3s;
        }
        
        input:focus, textarea:focus {
            outline: none;
            border-color: #3498db;
            box-shadow: 0 0 0 2px rgba(52, 152, 219, 0.2);
        }
        
        textarea {
            min-height: 100px;
            resize: vertical;
        }
        
        button {
            background: #3498db;
            color: white;
            border: none;
            padding: 14px 20px;
            border-radius: 8px;
            font-size: 16px;
            font-weight: 600;
            cursor: pointer;
            width: 100%;
            transition: background 0.3s;
        }
        
        button:hover {
            background: #2980b9;
        }
        
        .divider {
            height: 1px;
            background: #eee;
            margin: 25px 0;
        }
        
        .tasks-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
        }
        
        .tasks-title {
            font-size: 22px;
            color: #2c3e50;
            font-weight: 600;
        }
        
        .task-count {
            background: #3498db;
            color: white;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 14px;
        }
        
        .task-list {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }
        
        .task-item {
            background: #f8f9fa;
            border-left: 4px solid #3498db;
            border-radius: 8px;
            padding: 15px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        
        .

Dante, [8/25/2025 8:22 AM]
task-info h3 {
            color: #2c3e50;
            margin-bottom: 5px;
        }
        
        .task-info p {
            color: #7f8c8d;
            margin-bottom: 5px;
        }
        
        .task-date {
            color: #e74c3c;
            font-weight: 500;
        }
        
        .empty-state {
            text-align: center;
            color: #7f8c8d;
            padding: 40px 0;
        }
        
        .empty-state p {
            margin-top: 10px;
        }
        
        @media (max-width: 600px) {
            .planner-card {
                padding: 20px;
            }
            
            .task-item {
                flex-direction: column;
                align-items: flex-start;
                gap: 10px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="planner-card">
            <h1>Student Study Planner</h1>
            
            <form method="POST" action="">
                <div class="form-group">
                    <label for="subject">Subject</label>
                    <input type="text" id="subject" name="subject" placeholder="e.g. Mathematics" required>
                </div>
                
                <div class="form-group">
                    <label for="task">Task</label>
                    <textarea id="task" name="task" placeholder="Describe the study task..." required></textarea>
                </div>
                
                <div class="form-group">
                    <label for="due_date">Due Date</label>
                    <input type="date" id="due_date" name="due_date" required>
                </div>
                
                <button type="submit">Add To Planner</button>
            </form>
        </div>
        
        <div class="planner-card">
            <div class="tasks-header">
                <h2 class="tasks-title">Your Study Tasks</h2>
                <span class="task-count"><?php echo count($tasks); ?> tasks</span>
            </div>
            
            <div class="task-list">
                <?php if (!empty($tasks)): ?>
                    <?php foreach (array_reverse($tasks) as $index => $task): ?>
                        <div class="task-item">
                            <div class="task-info">
                                <h3><?php echo $task['subject']; ?></h3>
                                <p><?php echo $task['task']; ?></p>
                                <span class="task-date">Due: <?php echo date('m/d/Y', strtotime($task['due_date'])); ?></span>
                            </div>
                        </div>
                    <?php endforeach; ?>
                <?php else: ?>
                    <div class="empty-state">
                        <h3>No tasks yet</h3>
                        <p>Add your first study task using the form above</p>
                    </div>
                <?php endif; ?>
            </div>
        </div>
    </div>

    <script>
        // Set default date to today
        document.getElementById('due_date').valueAsDate = new Date();
        
        // Form validation
        document.querySelector('form').addEventListener('submit', function(e) {
            const subject = document.getElementById('subject').value.trim();
            const task = document.getElementById('task').value.trim();
            const dueDate = document.getElementById('due_date').value;
            
            if (!subject  !task  !dueDate) {
                e.preventDefault();
                alert('Please fill in all fields');
            }
        });
    </script>
</body>
</html>