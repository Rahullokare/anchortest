<template>
  <div>
    <h1 class="pb-5">Compare Packages</h1>

    <div class="table-responsive compare-packages">
      <table class="table table-bordered">
        <thead>
          <tr>
            <th width="240px">Package</th>
            <th>
              <p class="price" style="">₹ 600</p>
              <p class="plans mb-3">Basic</p>
              <p class="title">Gold</p>
              <p>Modern and professional landing page up to 5 sections</p>
            </th>
            <th>
              <p class="price" style="">₹ 600</p>
              <p class="plans mb-3">Standard</p>
              <p class="title">Sliver</p>

              <p>Modern and professional landing page up to 5 sections</p>
            </th>
            <th>
              <p class="price" style="">₹ 600</p>
              <p class="plans mb-3">Premium</p>
              <p class="title">Diamond</p>

              <p>Modern and professional landing page up to 5 sections</p>
            </th>
          </tr>
        </thead>
        <tbody>
          <tr style="background-color: #eefcfb">
            <td>Responsive</td>
            <td><i class="fa fa-check" aria-hidden="true"></i></td>
            <td><i class="fa fa-check" aria-hidden="true"></i></td>
            <td><i class="fa fa-check" aria-hidden="true"></i></td>
          </tr>

          <tr>
            <td>Source</td>
            <td><i class="fa fa-check" aria-hidden="true"></i></td>
            <td><i class="fa fa-check" aria-hidden="true"></i></td>
            <td><i class="fa fa-check" aria-hidden="true"></i></td>
          </tr>

          <tr style="background-color: #eefcfb">
            <td>Number of Sessions</td>
            <td>5</td>
            <td>5</td>
            <td>5</td>
          </tr>

          <tr>
            <td>Sessions At</td>
            <td>
              <div class="form-check">
                <input
                  class="form-check-input"
                  type="radio"
                  name="exampleRadios"
                  id="exampleRadios1"
                  value="option1"
                  checked
                />
                <label class="form-check-label" for="exampleRadios1">
                  Voice Call &nbsp;&nbsp; + $600
                </label>
              </div>
              <div class="form-check">
                <input
                  class="form-check-input"
                  type="radio"
                  name="exampleRadios"
                  id="exampleRadios2"
                  value="option2"
                />
                <label class="form-check-label" for="exampleRadios2">
                  Voice Call &nbsp;&nbsp; + $600
                </label>
              </div>
              <div class="form-check">
                <input
                  class="form-check-input"
                  type="radio"
                  name="exampleRadios"
                  id="exampleRadios1"
                  value="option1"
                  checked
                />
                <label class="form-check-label" for="exampleRadios1">
                  Voice Call &nbsp;&nbsp; + $600
                </label>
              </div>
            </td>
            <td>
              <div class="form-check">
                <input
                  class="form-check-input"
                  type="radio"
                  name="exampleRadios"
                  id="exampleRadios1"
                  value="option1"
                  checked
                />
                <label class="form-check-label" for="exampleRadios1">
                  Voice Call &nbsp;&nbsp; + $600
                </label>
              </div>
              <div class="form-check">
                <input
                  class="form-check-input"
                  type="radio"
                  name="exampleRadios"
                  id="exampleRadios2"
                  value="option2"
                />
                <label class="form-check-label" for="exampleRadios2">
                  Voice Call &nbsp;&nbsp; + $600
                </label>
              </div>
              <div class="form-check">
                <input
                  class="form-check-input"
                  type="radio"
                  name="exampleRadios"
                  id="exampleRadios1"
                  value="option1"
                  checked
                />
                <label class="form-check-label" for="exampleRadios1">
                  Voice Call &nbsp;&nbsp; + $600
                </label>
              </div>
            </td>
            <td>
              <div class="form-check">
                <input
                  class="form-check-input"
                  type="radio"
                  name="exampleRadios"
                  id="exampleRadios1"
                  value="option1"
                  checked
                />
                <label class="form-check-label" for="exampleRadios1">
                  Voice Call &nbsp;&nbsp; + $600
                </label>
              </div>
              <div class="form-check">
                <input
                  class="form-check-input"
                  type="radio"
                  name="exampleRadios"
                  id="exampleRadios2"
                  value="option2"
                />
                <label class="form-check-label" for="exampleRadios2">
                  Voice Call &nbsp;&nbsp; + $600
                </label>
              </div>
              <div class="form-check">
                <input
                  class="form-check-input"
                  type="radio"
                  name="exampleRadios"
                  id="exampleRadios1"
                  value="option1"
                  checked
                />
                <label class="form-check-label" for="exampleRadios1">
                  Voice Call &nbsp;&nbsp; + $600
                </label>
              </div>
            </td>
          </tr>

          <tr>
            <td>Total Prices</td>
            <td>₹600<br /></td>
            <td>₹600<br /></td>
            <td>₹600<br /></td>
          </tr>
          <tr>
            <td></td>
            <td>
              <button
                class="btn text-white px-5"
                style="background-color: #1dbf73"
              >
                Select
              </button>
            </td>
            <td>
              <button
                class="btn text-white px-5"
                style="background-color: #1dbf73"
              >
                Select
              </button>
            </td>
            <td>
              <button
                class="btn text-white px-5"
                style="background-color: #1dbf73"
              >
                Select
              </button>
            </td>
          </tr>
        </tbody>
      </table>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.fa-check {
  color: #19a463;
}
.title {
  text-transform: uppercase !important;
  font-size: 12px !important;
  line-height: 150% !important;
  margin-bottom: 8px !important;
  font-weight: bold !important;
}
.price {
  margin-bottom: 8px;
  font-size: 19px;
  line-height: 26px;
}
.compare-packages table thead th {
  border-bottom: 2px solid #dee2e6;
  vertical-align: middle;
}

.compare-packages table thead th p {
  font-size: 16px;
  font-weight: 400;
  color: #333;
}
.plans {
  font-size: 20px !important;
  color: #62646a !important;
  font-weight: bold !important;
}
.compare-packages table td {
  text-align: center;
}
.compare-packages table td:first-child {
  text-align: left;
}
.compare-packages table tr:last-child td {
  font-weight: bold;
  line-height: 40px;
  font-size: 20px;
}
</style>