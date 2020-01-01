---
---
<script src="https://kit.fontawesome.com/d26d24aff7.js" crossorigin="anonymous"></script>
<script>
    let installCommand = ""
    window.onload = function() {
        if (navigator.appVersion.indexOf("Win") != -1) installCommand = "``` ```";
        if (navigator.appVersion.indexOf("Mac") != -1) installCommand = "```brew install angr-management```";
        if (navigator.appVersion.indexOf("Linux") != -1) Name = installCommand = "```apt-get install angr-management```";
        document.getElementById('black_code').innerHTML = installCommand;
    }
</script>
<div class="m">
    <h1 class="title"> angr-management </h1>
    <p class="description">Introducing the beautiful new GUI for angr.</p>
    <br />
    <div class="buttons">
        <div>
            <a href="https://github.com/angr/angr-management/releases" target="_blank" rel="noopener">
                <span class="button dl">
                    <i class="fas fa-download"></i>&nbsp;&nbsp;&nbsp;Download angr-management
                </span>
            </a>
        </div>
        <div>
            <a href="https://github.com/angr/angr-management" target="_blank" rel="noopener">
                <span class="button">
                    <i class="fab fa-github"></i>&nbsp;&nbsp;&nbsp;angr-management on Github
                </span>
            </a>
        </div>
    </div>
    <br />
    <br />
    <div class="buttons">
        <!-- <div class="black_code" id="black_code">
            ```
            $ brew install angr-management
            ```
        </div> -->
    </div>
    <br />
    <img src="/img/angr-management-screenshot.png" alt="" class="screenshot">
</div>
</div>