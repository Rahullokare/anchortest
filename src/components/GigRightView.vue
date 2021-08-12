<template>
  <div class="contain">
    <div class="mt-5 fixedElement">
      <div class="nav-container">
        <ul class="nav mb-3 d-flex nav-pills" id="pills-tab" role="tablist">
          <li class="nav-item flex-fill" role="presentation">
            <button
              class="nav-link"
              id="pills-home-tab"
              data-bs-toggle="pill"
              data-bs-target="#pills-home"
              type="button"
              role="tab"
              aria-controls="pills-home"
              aria-selected="true"
            >
              Basic
            </button>
          </li>
          <li class="nav-item flex-fill" role="presentation">
            <button
              class="nav-link"
              id="pills-profile-tab"
              data-bs-toggle="pill"
              data-bs-target="#pills-profile"
              type="button"
              role="tab"
              aria-controls="pills-profile"
              aria-selected="false"
            >
              Standard
            </button>
          </li>
          <li class="nav-item flex-fill" role="presentation">
            <button
              class="nav-link"
              id="pills-contact-tab"
              data-bs-toggle="pill"
              data-bs-target="#pills-contact"
              type="button"
              role="tab"
              aria-controls="pills-contact"
              aria-selected="false"
            >
              Elite
            </button>
          </li>
        </ul>
        <div class="tab-content" id="pills-tabContent">
          <div
            class="tab-pane fade show active"
            id="pills-home"
            role="tabpanel"
            aria-labelledby="pills-home-tab"
          >
            <!-- content -->
            <div class="d-flex mt-3 justify-content-between">
              <p class="heading-sub">Basic</p>
              <p class="pricing">₹781</p>
            </div>
            <p>Modern and professional landing page up to 5 sections</p>

            <div class="d-flex">
              <p class="me-3"><i class="fas fa-clock"></i> 2 days delivery</p>
              <p>
                <svg
                  width="16"
                  height="16"
                  viewBox="0 0 16 16"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M4.50001 11.4999C6.40001 13.3999 9.60001 13.3999 11.5 11.4999C12.2 10.7999 12.7 9.7999 12.9 8.7999L14.9 9.0999C14.7 10.5999 14 11.8999 13 12.8999C10.3 15.5999 5.90001 15.5999 3.10001 12.8999L0.900012 15.0999L0.200012 8.6999L6.60001 9.3999L4.50001 11.4999Z"
                  ></path>
                  <path
                    d="M15.8 7.2999L9.40001 6.5999L11.5 4.4999C9.60001 2.5999 6.40001 2.5999 4.50001 4.4999C3.80001 5.1999 3.30001 6.1999 3.10001 7.1999L1.10001 6.8999C1.30001 5.3999 2.00001 4.0999 3.00001 3.0999C4.40001 1.6999 6.10001 1.0999 7.90001 1.0999C9.70001 1.0999 11.5 1.7999 12.8 3.0999L15 0.899902L15.8 7.2999Z"
                  ></path>
                </svg>
                1 Revision
              </p>
            </div>
            <div>
              <p>
                <i class="fa fa-check" aria-hidden="true"></i>&nbsp; 5 Designs
                Section
              </p>
              <p>
                <i class="fa fa-check" aria-hidden="true"></i>&nbsp; Responsive
                Design
              </p>
              <p>
                <i class="fa fa-check" aria-hidden="true"></i>&nbsp; Source File
              </p>
            </div>
            <div class="btn w-100 text-white" style="background-color: #1dbf73">
              Continue(₹ 600)
            </div>
          </div>
          <div
            class="tab-pane fade"
            id="pills-profile"
            role="tabpanel"
            aria-labelledby="pills-profile-tab"
          >
            <!-- content -->
            <div class="d-flex mt-3 justify-content-between">
              <p class="heading-sub">Standard</p>
              <p class="pricing">₹781</p>
            </div>
            <p>Modern and professional landing page up to 5 sections</p>

            <div class="d-flex">
              <p class="me-3"><i class="fas fa-clock"></i> 2 days delivery</p>
              <p>
                <svg
                  width="16"
                  height="16"
                  viewBox="0 0 16 16"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M4.50001 11.4999C6.40001 13.3999 9.60001 13.3999 11.5 11.4999C12.2 10.7999 12.7 9.7999 12.9 8.7999L14.9 9.0999C14.7 10.5999 14 11.8999 13 12.8999C10.3 15.5999 5.90001 15.5999 3.10001 12.8999L0.900012 15.0999L0.200012 8.6999L6.60001 9.3999L4.50001 11.4999Z"
                  ></path>
                  <path
                    d="M15.8 7.2999L9.40001 6.5999L11.5 4.4999C9.60001 2.5999 6.40001 2.5999 4.50001 4.4999C3.80001 5.1999 3.30001 6.1999 3.10001 7.1999L1.10001 6.8999C1.30001 5.3999 2.00001 4.0999 3.00001 3.0999C4.40001 1.6999 6.10001 1.0999 7.90001 1.0999C9.70001 1.0999 11.5 1.7999 12.8 3.0999L15 0.899902L15.8 7.2999Z"
                  ></path>
                </svg>
                1 Revision
              </p>
            </div>
            <div>
              <p>
                <i class="fa fa-check" aria-hidden="true"></i>&nbsp; 5 Designs
                Section
              </p>
              <p>
                <i class="fa fa-check" aria-hidden="true"></i>&nbsp; Responsive
                Design
              </p>
              <p>
                <i class="fa fa-check" aria-hidden="true"></i>&nbsp; Source File
              </p>
            </div>
            <div class="btn w-100 text-white" style="background-color: #1dbf73">
              Continue(₹ 600)
            </div>
          </div>
          <div
            class="tab-pane fade"
            id="pills-contact"
            role="tabpanel"
            aria-labelledby="pills-contact-tab"
          >
            <!-- content -->
            <div class="d-flex mt-3 justify-content-between">
              <p class="heading-sub">Elite</p>
              <p class="pricing">₹781</p>
            </div>
            <p>Modern and professional landing page up to 5 sections</p>

            <div class="d-flex">
              <p class="me-3"><i class="fas fa-clock"></i> 2 days delivery</p>
              <p>
                <svg
                  width="16"
                  height="16"
                  viewBox="0 0 16 16"
                  xmlns="http://www.w3.org/2000/svg"
                >
                  <path
                    d="M4.50001 11.4999C6.40001 13.3999 9.60001 13.3999 11.5 11.4999C12.2 10.7999 12.7 9.7999 12.9 8.7999L14.9 9.0999C14.7 10.5999 14 11.8999 13 12.8999C10.3 15.5999 5.90001 15.5999 3.10001 12.8999L0.900012 15.0999L0.200012 8.6999L6.60001 9.3999L4.50001 11.4999Z"
                  ></path>
                  <path
                    d="M15.8 7.2999L9.40001 6.5999L11.5 4.4999C9.60001 2.5999 6.40001 2.5999 4.50001 4.4999C3.80001 5.1999 3.30001 6.1999 3.10001 7.1999L1.10001 6.8999C1.30001 5.3999 2.00001 4.0999 3.00001 3.0999C4.40001 1.6999 6.10001 1.0999 7.90001 1.0999C9.70001 1.0999 11.5 1.7999 12.8 3.0999L15 0.899902L15.8 7.2999Z"
                  ></path>
                </svg>
                1 Revision
              </p>
            </div>
            <div>
              <p>
                <i class="fa fa-check" aria-hidden="true"></i>&nbsp; 5 Designs
                Section
              </p>
              <p>
                <i class="fa fa-check" aria-hidden="true"></i>&nbsp; Responsive
                Design
              </p>
              <p>
                <i class="fa fa-check" aria-hidden="true"></i>&nbsp; Source File
              </p>
            </div>
            <div class="btn w-100 text-white" style="background-color: #1dbf73">
              Continue(₹ 600)
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.contain {
  position: relative;
}
.fa-check {
  color: #19a463;
}

.heading-sub {
  color: #404145;
  font-weight: bold;
}
.pricing {
  color: #404145;
}
.fixedElement {
  /* background-color: #c0c0c0; */
  border: 1px solid #dadbdd;
  position: fixed;
  top: 150px;
  height: 800px;
  /* width: 100%; */

  /* overflow-y: scroll; */
  z-index: 100;
}
/* .nav-container { */
/* position: fixed;
  width: 400px; */
/* } */
.nav-item {
  border: 1px solid #dadbdd;
  /* padding: 16px; */
}

.nav-pills .nav-link.active,
.nav-pills .show > .nav-link {
  color: #1dbf73;
  border-bottom: 3px solid #1dbf73 !important;
  background-color: #fff;
  width: 100%;
}

.nav-link {
  display: block;
  padding: 0.5rem 1rem;
  width: 100%;
  text-decoration: none;
  border: none !important;
  color: #7a7d85;
  text-align: center;
  border-bottom: 1px solid #dadbdd;
  border-left: none;
  padding: 16px;
  -webkit-box-flex: 1;
}
.tab-pane {
  padding-left: 24px;
  padding-right: 24px;
}
</style>