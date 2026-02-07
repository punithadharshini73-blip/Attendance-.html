<html>
<head>
    <title>Attendance Management</title>
    <style>
        body {
            font-family: Arial;
            background: #eef2ff;
            text-align: center;
        }
        .box {
            background: white;
            width: 450px;
            margin: auto;
            padding: 20px;
            border-radius: 10px;
        }
        input {
            width: 90%;
            padding: 8px;
            margin: 5px;
        }
        button {
            padding: 6px 12px;
            margin: 5px;
            cursor: pointer;
        }
        table {
            width: 100%;
            margin-top: 15px;
        }
        th, td {
            padding: 8px;
        }
        .present { color: green; }
        .absent { color: red; }
    </style>
</head>
<body>

<h2>Attendance Management System</h2>

<div class="box">
    <input id="name" placeholder="Student Name">
    <button onclick="addStudent()">Add Student</button>

    <table border="1">
        <thead>
            <tr>
                <th>Name</th>
                <th>Status</th>
                <th>Mark</th>
                <th>Action</th>
            </tr>
        </thead>
        <tbody id="list"></tbody>
    </table>
</div>

<script>
function addStudent() {
    let name = document.getElementById("name").value;
    if(name === "") {
        alert("Enter name");
        return;
    }

}
</script>

</body>
</html>
