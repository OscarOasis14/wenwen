<!DOCTYPE html>
<html>

<head>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js"></script>

  <title>Web Programming Lab Feedback Form</title>


  <style>
    body {
      background: linear-gradient(#141e30, #7c90a7);
    }

    body,
    div,
    form,
    input,
    textarea,
    label {
      padding: 0;
      font-family: Roboto, Arial, sans-serif;
      font-size: 14px;
      color: black;
    }

    section {
      margin: 20px;
      padding: 20px;
      border-radius: 6px;
      background: linear-gradient(to right, #ffffff, #ffffff62);
    }

    span {
      color: red;
    }

    .first-col {
      width: 25%;
      text-align: left;
    }

    th,
    td {
      width: 10%;
      text-align: center;
      vertical-align: center;
    }

    .btn-block {
      text-align: center;
    }

    input[type="date"]::-webkit-calendar-picker-indicator {
      color: rgba(0, 0, 0, 0);
      opacity: 1;
      display: block;
      background: url(https://mywildalberta.ca/images/GFX-MWA-Parks-Reservations.png) no-repeat;
      cursor: pointer;
    }

    carousel-caption {
      top: 50%;
      transform: translateY(-50%);
    }

    .carousel-caption h1 {
      line-height: 45px;
      font-size: 45px;
      color: white;
    }

    .d-block {
      height: 250px;
    }


    html {
      scroll-padding-top: 70px;
    }

    @media (max-width: 750px) {
      form {
        background: red;
      }

      button {
        margin-bottom: 10px;
      }

      .carousel-caption {
        top: 55%;
        transform: translateY(-55%);
      }

      .carousel-caption h1 {
        font-size: 3vw;
        line-height: 25px;
      }
    }
  </style>
</head>

<body data-bs-spy="scroll" data-bs-target=".navbar" data-bs-offset="50">

  <nav class="navbar navbar-expand-sm bg-dark navbar-dark sticky-top">
    <div class="container-fluid">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link" href="#section1">Home Page</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#section2">Team Member</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#section3">Ticket Service</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="#section4">Ticket Service</a>
          </li>
      </ul>
    </div>
  </nav>

  <div class="container-fluid">
    <form action="action.php" method="post">

      <section id="section1">
        <!-- Carousel -->
        <div id="demo" class="carousel slide" data-bs-ride="carousel">

          <!-- Indicators/dots -->
          <div class="carousel-indicators">
            <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
            <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
            <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
          </div>

          <!-- The slideshow/carousel -->
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="Swk.jpg" alt="Banner1" class="d-block" style="width:100%">
              <div class="carousel-caption">
              </div>

            </div>
            <div class="carousel-item">
              <img src="swk2.jpg" alt="Banner2" class="d-block" style="width:100%">
              <div class="carousel-caption">
              </div>

            </div>
            <div class="carousel-item">
              <img src="Sarawak3.webp" alt="Banner3" class="d-block" style="width:100%">
              <div class="carousel-caption">
              </div>

            </div>
          </div>

          <!-- Left and right controls/icons -->
          <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
            <span class="carousel-control-prev-icon"></span>
          </button>
          <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
            <span class="carousel-control-next-icon"></span>
          </button>
        </div>

        <h4>Sarawak Culture Village</h4></p>

        <div class="container px-4 px-lg-5">
          <!-- Heading Row-->
          <div class="row gx-4 gx-lg-5 align-items-center my-5">
              <div class="col-lg-7"><img src="Sarawak.jpg" class="img-fluid rectangle" alt="ProfilePicture"></p></div>
              <div class="col-lg-5">
                  <h1 class="font-weight-light">About Sarawak Culture</h1>
                  <p>Sarawak Cultural Village is an award-winning Living Museum that spans across 17-acres of land just across from Damai Beach Resort and Hotels. Experience Sarawak in Half-a-day at Sarawak Cultural Village and learn about the local culture and lifestyles of the various ethnic groups in Sarawak.</p>

                  <p>At Sarawak Cultural Village, there are replica buildings representing every major ethnic group in Sarawak mainly the Bidayuh, Iban, Orang Ulu, Penan, Melanau, Malay & Chinese. All buildings are staﬀed with members of the ethnic groups in traditional costume and carrying out traditional activities. The staﬀs act as storytellers who describe and interpret our way of life. They will happily pose with you for photos too!</p>
                    
                  <p>Sarawak Cultural Village also has an award-winning dance troupe that will entertain you with our multi-cultural dance performance in our Village Theatre twice a day. Our cultural show runs twice a day at 11.30 am and 4 pm.</p>
              </div>
          </div>
        
    </form>
    </section>


    <section id="section2">
      <h1>My Team Member</h1>
      <div class="mb-3 mt-3">
        <div class="row">

            <!-- Content Row-->
            <div class="row gx-4 gx-lg-5">
              <div class="col-md-4 mb-5">
                  <div class="card h-100">
                      <div class="card-body">
                          <h2 class="card-title">Nia Elya Farhana</h2>
                          <img src="nia.jpg" class="img-fluid rectangle" alt="ProfilePicture"></p>
                          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem magni quas ex numquam, maxime minus quam molestias corporis quod, ea minima accusamus.</p>
                      </div>
                  
                  </div>
              </div>
              <div class="col-md-4 mb-5">
                  <div class="card h-100">
                      <div class="card-body">
                          <h2 class="card-title">Alicia Derllin Denis</h2>
                          <img src="fwen.jpg" class="img-fluid rectangle" alt="ProfilePicture"></p>
                          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Quod tenetur ex natus at dolorem enim! Nesciunt pariatur voluptatem sunt quam eaque, vel, non in id dolore voluptates quos eligendi labore.</p>
                      </div>
                  </div>
              </div>
              <div class="col-md-4 mb-5">
                  <div class="card h-100">
                      <div class="card-body">
                          <h2 class="card-title">Swaylin Aduat</h2>
                          <img src="Sarawak.jpg" class="img-fluid rectangle" alt="ProfilePicture"></p>
                          <p class="card-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Rem magni quas ex numquam, maxime minus quam molestias corporis quod, ea minima accusamus.</p>
                      </div>
                  </div>


          </div>

    </section>

    <section id="section3">
      <h1>My Team Member</h1>
      <div class="mb-3 mt-3">
        <div class="row">

          <div class="col-sm-4">
            <img src="fwen.jpg" class="img-fluid rectangle" alt="ProfilePicture"></p>
            <img src="fwen.jpg" class="img-fluid rectangle" alt="ProfilePicture"></p>
            <img src="fwen.jpg" class="img-fluid rectangle" alt="ProfilePicture"></p>
            <img src="fwen.jpg" class="img-fluid rectangle" alt="ProfilePicture">

          </div>

          <div class="col-sm-8">
            <p>Kami semua merupakan seorang jomblo dari first year
            
            </p>
            <br>
            <h4>Senarai nama kami sekaban</h4>
            <ul class="list-group">
              <li class="list-group-item">
                <b>Vestibulum molestie placerat</b>
                <br>
                neque, sed semper massa fringilla vitae. Praesent accumsan faucibus mi, sit amet
                vulputate augue aliquet et. Praesent placerat dui et sapien rhoncus, vulputate
                maximus nisi pulvinar <a href="https://youtu.be/dQw4w9WgXcQ">faucibus</a>
                iaculis magna sit amet, consequat felis.
              </li>

              <li class="list-group-item">
                <b>Nulla vel lacus tempor</b>
                <br>
                Fusce leo lectus, faucibus venenatis ex et, lobortis auctor risus.<a
                  href="https://youtu.be/dQw4w9WgXcQ">
                  lobortis</a> Ut a commodo ex. Pellentesque habitant morbi tristique senectus et netus et malesuada
                fames
                ac turpis egestas. Etiam sollicitudin eros nec dolor malesuada, at facilisis odio cursus.
              </li>
            </ul>
            <div class="mb-3 mt-3">
              <h6>Day <span>*</span></h6>
    
              <input class="form-control" type="date" name="day" required>
            </div>
    
    
            <div class="mb-3 mt-3">
              <h6>Lab Resources <span>*</span></h6>
              <div class="form-check">
                <label class="form-check-label"><input class="form-check-input" type="checkbox" value="Table"
                    name="lab_resource1"> Table</label>
              </div>
    
              <div class="form-check">
                <label class="form-check-label"><input class="form-check-input" type="checkbox" value="Chair"
                    name="lab_resource2"> Chair</label>
              </div>
    
              <div class="form-check">
                <label class="form-check-label"><input class="form-check-input" type="checkbox" value="Computer"
                    name="lab_resource3"> Computer</label>
              </div>
            </div>
            <table class="table table-bordered table-striped mt-5">
              <thead>
                <tr>
                  <th>Event</th>
                  <th>Date</th>
                  <th>Available Tickets</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td>Event 1</td>
                  <td>2024-12-01</td>
                  <td>50</td>
                </tr>
                <tr>
                  <td>Event 2</td>
                  <td>2024-12-05</td>
                  <td>100</td>
                </tr>
              </tbody>
            </table>
            <div class="mb-3 mt-3">
              <h6>Lab's Performance Evaluation <span>*</span></h6>
              <div class="table-responsive">
                <table class="table table-hover">
                  <tr>
                    <th class="first-col">Content</th>
                    <th>Strongly Agree</th>
                    <th>Agree</th>
                    <th>Neutral</th>
                    <th>Disagree</th>
                    <th>Strongly Disagree</th>
    
                  </tr>
                  
                  <tr>
                    <td class="first-col">The syllabus was explained at the beginning of the course.</td>
                    <td><input class="form-check-input" type="radio" value="1" name="Q1" /></td>
                    <td><input class="form-check-input" type="radio" value="2" name="Q1" /></td>
                    <td><input class="form-check-input" type="radio" value="3" name="Q1" /></td>
                    <td><input class="form-check-input" type="radio" value="4" name="Q1" /></td>
                    <td><input class="form-check-input" type="radio" value="5" name="Q1" /></td>
                  </tr>
    
                  <tr>
                    <td class="first-col">The course was delivered as outlined in the syllabus.</td>
                    <td><input class="form-check-input" type="radio" value="1" name="Q2" /></td>
                    <td><input class="form-check-input" type="radio" value="2" name="Q2" /></td>
                    <td><input class="form-check-input" type="radio" value="3" name="Q2" /></td>
                    <td><input class="form-check-input" type="radio" value="4" name="Q2" /></td>
                    <td><input class="form-check-input" type="radio" value="5" name="Q2" /></td>
                  </tr>
    
                  <tr>
                    <td class="first-col">The instructor was organized and prepared for every class</td>
                    <td><input class="form-check-input" type="radio" value="1" name="Q3" /></td>
                    <td><input class="form-check-input" type="radio" value="2" name="Q3" /></td>
                    <td><input class="form-check-input" type="radio" value="3" name="Q3" /></td>
                    <td><input class="form-check-input" type="radio" value="4" name="Q3" /></td>
                    <td><input class="form-check-input" type="radio" value="5" name="Q3" /></td>
                  </tr>
    
                </table>
              </div>
            </div>
    
            <div class="mb-3 mt-3">
              <h6>Overall Experience <span>*</span></h6>
              <input class="form-range" type="range" name="experience" min="0" max="100" required>
            </div>
    
            <div class="mb-3 mt-3">
              <h6>Any comments, questions or suggestions?</h6>
              <textarea class="form-control" name="comment" rows="5"
                placeholder="Please write your comments/questions/suggestions here if you have any"></textarea>
            </div>
    
    
            <div class="btn-block">
              <button class="btn btn-primary" type="reset">Reset</button>
              <button class="btn btn-primary" type="submit">Send Feedback</button>
            </div>

        </section>

                          <section id="section4">
                            <div class="mb-3 mt-3">
                              <div class="row">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ticketing Page</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .card {
      margin: 10px 0;
    }
    @media (max-width: 768px) {
      .card-title {
        font-size: 16px;
      }
      .card-text {
        font-size: 14px;
      }
    }
  </style>
</head>
<body>
  <header class="bg-primary text-white text-center py-3">
    <h1>Ticket Booking System</h1>
    <p>Book tickets for your favorite events seamlessly</p>
  </header>

  <main class="container mt-5">
    <!-- Event Selection Section -->
    <section>
      <h2 class="mb-4">Available Events Everyday</h2>
      <div class="row" id="events-container">
        <!-- Event cards will be dynamically inserted here -->
        <table class="table table-bordered table-striped mt-5">
            <thead>
              <tr>
                <th>Event</th>
                <th>Time</th>
                <th>Available Tickets</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td>Cultural Show 1</td>
                <td>11:30am</td>
                <td>100</td>
              </tr>
              <tr>
                <td>Cultural Show 2</td>
                <td>4:00pm</td>
                <td>100</td>
              </tr>
            </tbody>
          </table>
      </div>
    </section>

    <!-- Booking Form Section -->
    <section class="mt-5">
      <h2>Book Your Ticket</h2>
            <!-- Options populated dynamically -->
          </select>
        </div>
        <div class="mb-3">
          <label for="userName" class="form-label">Your Name<span>*</span></label>
          <input type="text" id="userName" class="form-control" placeholder="Enter your name" required>
        </div>
        <div class="mb-3">
          <label for="userEmail" class="form-label">Email Address<span>*</span></label>
          <input type="email" id="userEmail" class="form-control" placeholder="Enter your email" required>
        </div>
        <div class="mb-3">
            <label for="eventName" class="form-label">Select Date<span>*</span></label>
                <input class="form-control" type="date" name="day" required>
              </div>
              <div class="mb-3 mt-3">
                <label for="selectshow" class="form-label">Select Show</label>
                <div class="form-check">
                  <label class="form-check-label"><input class="form-check-input" type="checkbox" value="Table"
                      name="lab_resource1"> Show 1</label>
                </div>
      
                <div class="form-check">
                  <label class="form-check-label"><input class="form-check-input" type="checkbox" value="Chair"
                      name="lab_resource2"> Show 2</label>
                </div>
              </div>
        <div class="mb-3">
          <label for="ticketCount" class="form-label">Number of Tickets</label>
          <input type="number" id="ticketCount" class="form-control" min="1" placeholder="Enter ticket quantity" required>
        </div>
        
  
          <div class="mb-3 mt-3">
            <h6>Any additional requirement?</h6>
            <textarea class="form-control" name="comment" rows="5"
              placeholder="Please write your additional requirement here "></textarea>
          </div>
        <button type="submit" class="btn btn-success">Book Tickets</button>
      </form>
    </section>
  </main>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
  <script>
    // Sample data for events
    const events = [
      { id: 1, name: "Music Concert", date: "2024-12-01", availableTickets: 50 },
      { id: 2, name: "Art Exhibition", date: "2024-12-05", availableTickets: 30 },
      { id: 3, name: "Theater Play", date: "2024-12-10", availableTickets: 20 }
    ];

    // Function to populate event cards
    function populateEvents() {
      const eventsContainer = document.getElementById('events-container');
      const eventDropdown = document.getElementById('eventName');
      events.forEach(event => {
        // Add cards
        const card = `
          <div class="col-md-4 col-sm-6">
            <div class="card">
              <div class="card-body">
                <h5 class="card-title">${event.name}</h5>
                <p class="card-text">Date: ${event.date}</p>
                <p class="card-text">Available Tickets: ${event.availableTickets}</p>
              </div>
            </div>
          </div>`;
        eventsContainer.innerHTML += card;

        // Add dropdown options
        const option = <option value="${event.id}">${event.name} - ${event.date}</option>;
        eventDropdown.innerHTML += option;
      });
    }

    // Function to handle ticket booking
    function handleFormSubmit(e) {
      e.preventDefault();
      const selectedEventId = document.getElementById('eventName').value;
      const userName = document.getElementById('userName').value;
      const userEmail = document.getElementById('userEmail').value;
      const ticketCount = parseInt(document.getElementById('ticketCount').value);

      if (!selectedEventId || !userName || !userEmail || !ticketCount) {
        alert("Please fill out all fields!");
        return;
      }

      // Find selected event
      const selectedEvent = events.find(event => event.id == selectedEventId);

      // Check ticket availability
      if (ticketCount > selectedEvent.availableTickets) {
        alert("Not enough tickets available!");
        return;
      }

      // Update available tickets
      selectedEvent.availableTickets -= ticketCount;

      // Confirm booking
      alert("Success! You have booked ${ticketCount} ticket(s) for ${selectedEvent.name}.");
      document.getElementById('ticketForm').reset();

      // Refresh events
      document.getElementById('events-container').innerHTML = '';
      populateEvents();
    }

    // Initialize page
    populateEvents();
    document.getElementById('ticketForm').addEventListener('submit', handleFormSubmit);
  </script>
</body>
</html>


                              </div>
   


                          </section>
                          
    
   

  </div>
</body>

</html>
