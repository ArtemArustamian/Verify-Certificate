<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>English Certificate - Artem Arustamian</title>
    <style>
        body {
            font-family: 'Times New Roman', serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }
        
        .certificate-container {
            width: 11in;
            height: 8.5in;
            background-image: url('https://images.unsplash.com/photo-1588072432836-e10032774350?ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80');
            background-size: cover;
            background-position: center;
            position: relative;
            box-shadow: 0 0 20px rgba(0,0,0,0.3);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: #333;
        }
        
        .certificate-content {
            text-align: center;
            padding: 2in;
            background-color: rgba(255, 255, 255, 0.85);
            border: 15px double #1a3e72;
            margin: 0.5in;
        }
        
        .name {
            font-size: 48px;
            font-weight: bold;
            margin: 20px 0;
            color: #1a3e72;
        }
        
        .level {
            font-size: 28px;
            font-weight: bold;
            margin: 15px 0;
            color: #2a5885;
        }
        
        .serial {
            font-size: 16px;
            font-family: 'Courier New', monospace;
            margin-top: 30px;
            color: #555;
        }
        
        .date {
            font-size: 18px;
            margin-top: 10px;
        }
        
        @media print {
            body {
                background: none;
            }
            .certificate-container {
                box-shadow: none;
                width: 100%;
                height: 100%;
            }
        }
    </style>
</head>
<body>
    <div class="certificate-container">
        <div class="certificate-content">
            <div class="name">Artem Arustamian</div>
            
            <div class="level">B2 Upper-Intermediate English Level</div>
            
            <div class="date">03/04/2017</div>
            
            <div class="serial">
                735F880B36-735F880B87-735F87C093
            </div>
        </div>
    </div>
</body>
</html>
