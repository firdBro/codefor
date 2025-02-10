# codefor
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>График снижения риска</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }
        table {
            width: 50%;
            border-collapse: collapse;
            text-align: center;
        }
        th, td {
            border: 1px solid black;
            padding: 10px;
        }
        .low-risk { background-color: green; color: white; }
        .medium-risk { background-color: yellow; color: black; }
        .high-risk { background-color: red; color: white; }
    </style>
</head>
<body>
    <h1>График снижения риска</h1>
    <table>
        <thead>
            <tr>
                <th>Вероятность воздействия</th>
                <th>1</th>
                <th>2</th>
                <th>3</th>
                <th>4</th>
                <th>5</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Редкий</td>
                <td class="low-risk">1</td>
                <td class="low-risk">1</td>
                <td class="medium-risk">2</td>
                <td class="medium-risk">3</td>
                <td class="high-risk">4</td>
            </tr>
            <tr>
                <td>Маловероятный</td>
                <td class="low-risk">1</td>
                <td class="medium-risk">2</td>
                <td class="medium-risk">3</td>
                <td class="high-risk">4</td>
                <td class="high-risk">5</td>
            </tr>
            <tr>
                <td>Возможный</td>
                <td class="medium-risk">2</td>
                <td class="medium-risk">3</td>
                <td class="high-risk">4</td>
                <td class="high-risk">5</td>
                <td class="high-risk">5</td>
            </tr>
            <tr>
                <td>Вероятный</td>
                <td class="medium-risk">3</td>
                <td class="high-risk">4</td>
                <td class="high-risk">5</td>
                <td class="high-risk">5</td>
                <td class="high-risk">5</td>
            </tr>
            <tr>
                <td>Почти наверняка</td>
                <td class="high-risk">4</td>
                <td class="high-risk">5</td>
                <td class="high-risk">5</td>
                <td class="high-risk">5</td>
                <td class="high-risk">5</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
