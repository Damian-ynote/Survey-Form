<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="style.css">
    <title>Survey Form</title>
</head>

<body>
    <h1 id="title">Survey Form</h1>

    <div id="main" class="container">

        <p id="description">Let us know how we can improve freeCodeCamp</p>

        <form action="" id="survey-form">
            <div class="in-line">
                <div class="labels">
                    <label for="" id="name-label">*Name:</label>
                </div>

                <div class="right">
                    <input autofocus name="name" type="text" id="name" class="input_" placeholder="Enter your name" required>
                </div>
            </div>

            <div class="in-line">
                <div class="labels">
                    <label for="email" id="email-label">*Email:</label>
                </div>

                <div class="right">
                    <input name="email" type="email" id="email" class="input_" placeholder="Enter your email" required>
                </div>
            </div>

            <div class="in-line">
                <div class="labels">
                    <label for="age" id="number-label">*Age:</label>
                </div>

                <div class="right">
                    <input name="age" type="number" id="number" class="input_" placeholder="Age" min="15" max="75">
                </div>
            </div>

            <div class="in-line">
                <div class="labels" id="dropdown-label">
                    <label for="role">Which option best describes your current role?</label>
                </div>

                <div class="right">
                    <select name="role" id="dropdown" class="dropdown">
                        <option disabled value>Select an option</option>
                        <option value="student">Student</option>
                        <option value="full time job">Full Time Job</option>
                        <option value="full time learner">Full Time Learner</option>
                        <option value="prefer not">Prefer not to say</option>
                        <option value="other">Other</option>
                    </select>
                </div>
            </div>

            <div class="in-line">

                <div class="labels">
                    <label for="rating" id="rating-label">* How likely is that you would recommend<br>freeCodeCamp to a friend?</label>
                </div>

                <div class="right">
                    <ul id="rating" style="list-style: none;">
                        <li class="radio">
                            <input name="radio" type="radio" value="1" class="ratings">
                            <label>Definitely</label>
                        </li>
                        <li class="radio">
                            <input name="radio" type="radio" value="1" class="ratings">
                            <label>Maybe</label>
                        </li>
                        <li class="radio">
                            <input name="radio" type="radio" value="1" class="ratings">
                            <label>Not Sure</label>
                        </li>
                    </ul>
                </div>

            </div>

            <div class="in-line">
                    <div class="labels" id="dropdown-label">
                        <label for="like">What do you like most in FCC:</label>
                    </div>
    
                    <div class="right">
                        <select name="like" id="dropdown1" class="dropdown">
                            <option disabled selected value>Select an option</option>
                            <option value="challenges">Challenges</option>
                            <option value="projects">Projects</option>
                            <option value="community">Community</option>
                            <option value="open source">Open Source</option>
                        </select>
                    </div>
            </div>

            <div class="in-line">

                    <div class="labels">
                        <label for="improvement">Things that should be improved in the future<br>
                                (Check all that apply):</label>
                    </div>
    
                    <div class="right">
                        <ul id="improvement" style="list-style: none;">
                            <li class="checkbox">
                                <input name="radio" type="checkbox" multiple value="1" class="ratings">
                                <label>Front-end Projects</label>
                            </li>
                            <li class="checkbox">
                                <input name="radio" type="checkbox" multiple value="1" class="ratings">
                                <label>Back-end Projects</label>
                            </li>
                            <li class="checkbox">
                                <input name="radio" type="checkbox" multiple value="1" class="ratings">
                                <label>Data Visualization</label>
                            </li>
                            <li class="checkbox">
                                <input name="radio" type="checkbox" multiple value="1" class="ratings">
                                <label>Challenges</label>
                            </li>
                            <li class="checkbox">
                                <input name="radio" type="checkbox" multiple value="1" class="ratings">
                                <label>Open Source Community</label>
                            </li>
                            <li class="checkbox">
                                <input name="radio" type="checkbox" multiple value="1" class="ratings">
                                <label>Gitter help rooms</label>
                            </li>
                            <li class="checkbox">
                                <input name="radio" type="checkbox" multiple value="1" class="ratings">
                                <label>Videos</label>
                            </li>
                            <li class="checkbox">
                                <input name="radio" type="checkbox" multiple value="1" class="ratings">
                                <label>City Meetups</label>
                            </li>
                            <li class="checkbox">
                                <input name="radio" type="checkbox" multiple value="1" class="ratings">
                                <label>Wiki</label>
                            </li>
                            <li class="checkbox">
                                <input name="radio" type="checkbox" multiple value="1" class="ratings">
                                <label>Forum</label>
                            </li>
                            <li class="checkbox">
                                <input name="radio" type="checkbox" multiple value="1" class="ratings">
                                <label>Additional Courses</label>
                            </li>
                            
                        </ul>
                    </div>
    
                </div>

                <div class="in-line">
                    <div class="labels">
                        <label for="comments">Any Comments or Suggestions?</label>
                    </div>

                    <div class="right">
                    <textarea name="comments" id="comments" class="textarea" placeholder="Enter your message here..." ></textarea>
                    </div>

                </div>

                <button id="submit" type="submit">Submit</button>


        </form>
    </div>

    
</body>
</html>
