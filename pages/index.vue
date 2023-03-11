<template>
  <div>
    <div class="body">
      <div class="card-body">
        <div class="card-body__content">
          <div class="qrcode"></div>
          <div class="card-body__text">
            <h2 class="title">Improve your front-end skills by building projects</h2>
            <p class="text">
              Scan the QR code to visit Frontend Mentor and take your coding skills to the next level
            </p>
          </div>
        </div>
      </div>
    </div>

    <attribution />
  </div>
</template>

<style scoped>
.body {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 50px;
}

.card-body {
  max-width: 100%;
  max-height: 100%;
  background-color: var(--white);
  border-radius: 20px;
  box-shadow: 0px 222px 89px rgba(0, 0, 0, 0.01), 0px 125px 75px rgba(0, 0, 0, 0.05), 0px 56px 56px rgba(0, 0, 0, 0.09), 0px 14px 31px rgba(0, 0, 0, 0.1), 0px 0px 0px rgba(0, 0, 0, 0.1);
  display: grid;
  width: 320px;
  height: 497px;
  align-content: space-between;
  justify-content: center;
}

.card-body__content {
  margin-top: 20px;
}

.card-body__text {
  width: 288px;
  height: max-content;
}

.qrcode {
  border-radius: 10px;
  width: 288px;
  height: 288px;
  background-image: url("~/static/images/image-qr-code.png");
  background-position: center;
  background-size: contain;
  margin-bottom: 25px;
}

.title {
  font-weight: var(--fwBold);
  line-height: 30px;
  text-align: center;
  letter-spacing: -0.03em;
  font-size: 24px;
  padding-bottom: 10px;
  color: var(--darkGreyBlue);
}

.text {
  text-align: center;
  color: var(--pureGrey);
  letter-spacing: 0.025em;
}

p,
span {
  font-size: var(--forParagraph);
}


@media screen and (max-width: 375px) {
  .body {
    margin: 0px;
  }

  .container {
    flex-direction: column;
  }


}
</style>


