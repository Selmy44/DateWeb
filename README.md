# DateWeb
This is A dating website
<!DOCTYPE html>
<html>
<head>
    <title>My Dating Website</title>
    <style>
        /* Inline CSS for simplicity, but it's recommended to use an external stylesheet */
        body {
            font-family: Arial, sans-serif;
        }
        .header {
            background-color: #f2f2f2;
            padding: 20px;
            text-align: center;
        }
        .profile {
            border: 1px solid #ccc;
            padding: 20px;
            margin: 10px;
            width: 300px;
            display: inline-block;
        }
        #profile-list {
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Welcome to My Dating Website</h1>
        <p>Find your perfect match!</p>
    </div>

    <div id="profile-list">
        <div class="profile">
            <img src="profile1.jpg" alt="Profile 1">
            <h2>John Doe</h2>
            <p>Age: 28</p>
            <p>Hobbies: Hiking, Cooking</p>
            <button onclick="likeProfile(1)">Like</button>
        </div>

        <div class="profile">
            <img src="profile2.jpg" alt="Profile 2">
            <h2>Jane Smith</h2>
            <p>Age: 25</p>
            <p>Hobbies: Reading, Traveling</p>
            <button onclick="likeProfile(2)">Like</button>
        </div>
    </div>

    <script>
        // JavaScript for liking a profile
        function likeProfile(profileId) {
            alert('You liked Profile ' + profileId);
        }
    </script>
</body>
</html>
