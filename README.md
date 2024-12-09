# hicet
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Simple Calculator</title>
            <style>
                body {
                    font-family: Arial, sans-serif;
                    display: flex;
                    justify-content: center ;
                    align-items: center; 
                    height: 100vh; 
                    background-color: #ffffff;
                }
                .calculator {
                    border: 2px solid #ccc; 
                    border-radius: 15px; 
                    padding: 20px; 
                    background-color: white;
                    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);    
                }
                .display { 
                    width: 85%; 
                    height: 50px;
                    text-align: right; 
                    padding: 010px; 
                    font-size: 24px;
                    border: 2 px solid #ccc; 
                    border-radius: 5px; 
                    margin-bottom: 10px;
                }
                .button {
                    width: 60px; 
                    height: 60px;
                    font-size: 20px; 
                    margin: 5px; 
                    border-radius: 5px; 
                    border: none;
                    background-color: #007bff; 
                    color: white;
                    cursor: pointer;
                }
                .button:hover {
                    transform: translatey(-5px);
                    background-color: #0056b3;
                }
            </style>
    </head>
    <body>
        <div class="calculator">
            <input type="text" class="display" value="" placeholder="0" readonly>
                <div>
                    <button class="button">7</button>
                    <button class="button">8</button>
                    <button class="button">9</button>
                    <button class="button">/</button>
                </div>

                <div>
                    <button class="button">4</button>
                    <button class="button">5</button>
                    <button class="button">6</button>
                    <button class="button">*</button>
                </div>

                <div>
                    <button class="button">1</button>
                    <button class="button">2</button>
                    <button class="button">3</button>
                    <button class="button">-</button>
                </div>

                <div>
                    <button class="button">0</button>   
                    <button class="button">C</button> 
                    <button class="button">=</button> 
                    <button class="button">+</button>
                </div>
        </div>
    </body>
</html>
