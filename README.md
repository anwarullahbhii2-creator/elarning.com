body {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    /* Aapki image ka path yahan aayega */
    background: url('image_fc2cb9.png') no-repeat center center fixed; 
    background-size: cover;
    position: relative;
}

/* Background ko thoda dark karne ke liye overlay (Optional) */
body::before {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.4); /* Isse login box zyada clear dikhega */
    z-index: -1;
}

.login-box {
    position: relative;
    width: 400px;
    padding: 40px;
    /* Box ko glass look dene ke liye thoda transparent rakha hai */
    background: rgba(0, 0, 0, 0.85); 
    border-radius: 10px;
    overflow: hidden;
    backdrop-filter: blur(5px); /* Trendy glassmorphism effect */
    box-shadow: 0 15px 25px rgba(0,0,0,.6);
}
