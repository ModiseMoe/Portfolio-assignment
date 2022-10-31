This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).



Made it responsive by adding an @media only screen query 

and added further css styling on the navigation menu, mobile menu(added a mobile menu class), active menu(added active menu class), logo ..etc

code

@media only screen and (max-width: 992px) {
  .navigation {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: #171f3897;
    z-index: 99999;
    display: none;
  }

  .nav__menu {
    position: absolute;
    top: 0;
    right: 0;
    width: 300px;
    height: 100%;
    flex-direction: column;
    justify-content: center;
  }

  .nav__right {
    display: none;
  }

  .mobile__menu {
    display: block !important;
  }

  .menu__active {
    display: block !important;
  }
