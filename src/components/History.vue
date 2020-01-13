<template>
  <div>
    <div>
      <div class="batch1">
        <h6>Assessment History</h6>
      </div>
    </div>
    <div>
      <table class="table">
        <thead class="table-head">
          <tr>
            <th scope="col">Name</th>
            <th scope="col">Email</th>
            <th scope="col">DOB - Age</th>
            <th scope="col">Adress</th>
            <th scope="col">University</th>
            <th scope="col">CGPA</th>
          </tr>
        </thead>
        <tbody class="table borderless">
          <tr class="different-row">
            <td>Ify Chinke</td>
            <td>ify@enyata.com</td>
            <td>12/09/19 - 22</td>
            <td>3 Sabo Ave, Yaba, Lagos</td>
            <td>University of Nigeria</td>
            <td>5.0</td>
          </tr>
          <tr>
            <td>Ify Chinke</td>
            <td>ify@enyata.com</td>
            <td>12/09/19 - 22</td>
            <td>3 Sabo Ave, Yaba, Lagos</td>
            <td>University of Nigeria</td>
            <td>5.0</td>
          </tr>
          <tr>
            <td>Ify Chinke</td>
            <td>ify@enyata.com</td>
            <td>12/09/19 - 22</td>
            <td>3 Sabo Ave, Yaba, Lagos</td>
            <td>University of Nigeria</td>
            <td>5.0</td>
          </tr>
        </tbody>
      </table>
    </div>
     <div class="container">
      <div class="container-side">
        <p>15/30</p>
        <!-- <p class="dot-text">+ Choose File</p> -->
        <input type="text" placeholder="+ Choose File" class="form" />
      </div>
      <div class="right">
        <p>Set Time</p>
        <div class="span">
          <div>
            <span>00<span class="minute">min</span></span>
            <img src="../assets/Polygon.png" alt="" />
          </div>
          <div>
            <span class="seconds">000<span class="minute">sec</span></span>
            <img src="../assets/Polygon.png" alt="" />
          </div>
        </div>
      </div>
      <button class="edit-button">Edit</button>
    </div>
    <div class="question-space">
      <h5>Question</h5>
      <input type="text" />
    </div>
    <form class="whole-form">
      <div class="form-row">
        <div class="form-group col-md-6">
          <label>Option A</label>
          <input type="text" class="form-control" />
        </div>
        <div class="form-group col-md-6">
          <label>Option B</label>
          <input type="text" class="form-control" />
        </div>
      </div>

      <div class="form-row">
        <div class="form-group col-md-6">
          <label>Option C</label>
          <input type="text" class="form-control" />
        </div>
        <div class="form-group col-md-6">
          <label>Option D</label>
          <input type="text" class="form-control" />
        </div>
      </div>
    </form>
    <div>
      <!-- <div class="two-buttons">
        <button class="first-button">Previous</button>
        <button class="second-button">Next</button>
      </div> -->
      <button class="last-button">Next</button>
    </div>
  </div>
</template>

<style scoped>
.different-row {
  background: #ffffff;
  box-shadow: 8px 18px 20px rgba(79, 79, 79, 0.3);
  border-radius: 10px;
  font-weight: bold;
  color: #2b3c4e;
  border-left: 10px solid #31d283;
}
.table-head {
  background: #2b3c4e;
  color: white;
}
.table {
    background: #FFFFFF;
    box-shadow: 8px 18px 20px rgba(79, 79, 79, 0.3);
    border-radius: 8px;
}
.borderless td,
.borderless th {
  border: none;
}
.batch1 {
  display: flex;
}
img {
  width: 12px;
  height: 12px;
  margin-left: 30px;
  margin-top: 20px;
}
h6 {
  font-family: Lato;
  font-style: normal;
  font-weight: 300;
  font-size: 43.5555px;
  line-height: 52px;
  color: #2b3c4e;
}
p {
  font-family: Lato;
  font-style: italic;
  font-weight: normal;
  font-size: 13px;
  line-height: 16px;
  color: #2b3c4e;
}

.edit-button {
    background: #FF9900;
    border-radius: 4px;
    width: 125px;
    height: 41px;
    color: white;
    margin-top: 160px;
    margin-left: 25px;
    border:none;
}

body {
  font-family: Lato;
}
span {
  font-family: Lato;
  font-style: normal;
  font-weight: 300;
  font-size: 48px;
}
.question-space {
  margin-top: 40px;
}
.seconds {
  padding-left: 30px;
}
.minute {
  font-family: Lato;
  font-style: normal;
  font-weight: normal;
  font-size: 12px;
  line-height: 14px;
}

.last-button {
  margin-left: 300px;
  margin-top: 60px;
  background: #2B3C4E;
  border-radius: 4px;
  width: 379px;
  height: 51px;
  color: white;
   border: none;
}
.second-button {
  background: #2b3c4e;
  border-radius: 4px;
  color: white;
  width: 125px;
  height: 41px;
   border: none;
}
.first-button {
  background: #2b3c4e;
  border-radius: 4px;
  color: white;
  width: 125px;
  height: 41px;
  border: none;
}
.two-buttons {
  display: flex;
  margin-left: 0px;
  margin-top: 50px;
  justify-content: space-around;
}

input {
  width: 976px;
  height: 144px;
}
.container-side {
  margin-top: 90px;
}
.container-side p {
  font-family: Lato;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 19px;
}
.span {
  display: flex;
}
.right {
  margin-top: 120px;
  margin-left: 150px;
}
.container {
  display: flex;
}
.form {
  border: 1.55172px dashed #2b3c4e;
  box-sizing: border-box;
  border-radius: 6.2069px;
  height: 108px;
  width: 450px;
}
h1 {
  font-family: Lato;
  font-style: normal;
  font-weight: 300;
  font-size: 43.5555px;
  line-height: 52px;
  letter-spacing: -0.02em;
  color: #2b3c4e;
}
form {
  padding-top: 30px;
}
.text {
  color: #1abc9c;
  font-size: 20px;
  font-family: "Roboto Condensed", serif;
  font-weight: 400;
  margin-top: 10px;
  margin-bottom: 10px;
  text-align: center;
}
.icon {
  margin-right: 15px;
}
.form-control {
  border: 1.5px solid #2b3c4e;
  height: 41px;
  box-sizing: border-box;
  border-radius: 4px;
  width: 456px;
}
</style>
