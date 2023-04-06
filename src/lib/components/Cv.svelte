<div id="cv" class="cv">
    <section>
        <h2>Skills</h2>
        <p><b>Language:</b> Swedish (Native), English (Proficient)</p>
        <p><b>Technologies and tools:</b> C#, .Net, Azure, Optimizely CMS (former Episerver), Javascript, Typescript, React, CSS, HTML (amongst others)</p>
    </section>
    <section>
        <h2>Previous projects</h2>
        <p>
            Management of and new development for NCC's intranet as well as external sites, development of a
            completely new site with a webshop for Styrelseakademien and bringing an MVP for the fintech
            startup Charly to market.
        </p>
    </section>
    <section>
        <h2>Experience</h2>
        <div class="work">
            <div class="item">
                <p class="employer">Alster (previously Isotop)</p>
                <p class="position">Full Stack Developer</p>
                <p class="time-period">2022</p>
            </div>
            <div class="item">
                <p class="employer">Isotop</p>
                <p class="position">Backend Developer</p>
                <p class="time-period">2018</p>
            </div>
            <div class="item">
                <p class="employer">SVT</p>
                <p class="position">Acting Team Manager</p>
                <p class="time-period">Aug 2015-Oct 2015</p>
            </div>
            <div class="item">
                <p class="employer">SVT</p>
                <p class="position">Live Subtitler</p>
                <p class="time-period">2011-2018</p>
            </div>
        </div>
    </section>
    <section>
        <h2>Education</h2>
        <div class="education">
            <div class="item">
                <p class="school">Nackademin</p>
                <p class="major">Software Development .NET</p>
                <p class="time-period">2016-2018</p>
            </div>
        </div>
    </section>
</div>

<style>
    /* Small screens */
    @media screen and (max-width: 600px) {
        .item {
            display: flex !important;
            flex-direction: column;
        }
        .work {
            gap: 1rem;
        }
        p {
            margin: 4px 8px;
        }
        .employer, .school {
            font-weight: 600;
            order: 2;
        }
        .position, .major {
            order: 3;
        }
        .time-period {
            order: 1;
            font-size: 0.8em;
        }
    }
    .cv {
        padding: 3rem 0;
    }
    .work {
        display: flex;
        flex-direction: column;
    }
    .item {
        display: grid;
        grid-auto-flow: column;
        grid-auto-columns: 1fr;
    }
    section {
        padding-bottom: 1rem;
    }
    b {
        font-family: 'Montserrat', sans-serif;
    }
    p {
        font-family: 'Libre Baskerville', serif;
        margin-left: 0;
    }
    h2 {
        font-family: 'Montserrat', sans-serif;
        text-align: left;
    }
</style>