<template>
    <div class="bio">
        <h1>Alison<br>Bickett, P.E.</h1>
        <h3 class="text-mute mt-4">Civil Engineer</h3>


        <div class="personal-info">
            <h4 class="heading">Info</h4>

            <div class="subheading">
                <b-icon icon="geo-alt-fill" class=""></b-icon>
                <div class="info">
                    Naples FL
                </div>
            </div>

            <div class="subheading">
                <b-icon icon="linkedin"></b-icon>
                <a href="https://www.linkedin.com/in/alison-bickett-p-e-a8342a13/" target="_blank" rel="noopener noreferrer">LinkedIn</a>
            </div>

            <div class="subheading">
                <b-icon icon="envelope-fill"></b-icon>
                <a href="mailto:ABickett@naplesgov.com">ABickett@naplesgov.com</a>
            </div>

        

        </div>

        <div class="education">
            <h4 class="heading">Education</h4>

            <h5 class="degree">Master of Engineering with Environmental Certificate, Civil &amp; Environmental Engineering</h5>
            <small>University of Louisville</small><br>
            <small>Fall 2001</small>


            <h5 class="degree">BS, Civil Engineering</h5>
            <small>University of Louisville</small><br>
            <small>Spring 2001</small>

        </div>



        <div class="honors">
            <h4 class="heading">Honors &amp; Activies</h4>
            <h6>Florida Engineering Society</h6>
            <ul>
                <li>State Communications Committee (2009-2018)<br>
                    Committee Chair (2014-2018)
                </li>
                <li>FES Journal - Published article (July 2010)<br>
                    "How the Economy Has Impacted the Engineering Profession"
                </li>
                <li>
                    Public Presenter - ITE 2017 Summer<br>
                    "Transportation Safety Summit-Planning through Design, Safety by Operation"
                </li>
            </ul>

            <h6>FES Calusa Chapter</h6>
            <ul>
                <li><strong>Young Engineer of the Year Award</strong> (2010)</li>
                <li>Past-President (2013)</li>
                <li>President (2012)</li>
                <li>Vice President (2011)</li>
                <li>Secretary (2010)</li>
                <li>Treasurer (2009)</li>
                <li>Professional Development Director &amp; Awards Chair (2013 - Present)</li>
            </ul>

            <h6>Activies</h6>
            <ul>
                <li>RRCA Certified Coach</li>
                <li>Certified Group Exercise Instructor</li>
                <li>Leukemia &amp; Lymphoma Society<br>
                    Team in Training<br>
                    Naples Head Runnning Coach<br>
                    (2002-2007)
                </li>
                <li>Society of Women Engineers speaker</li>
            </ul>


        </div>

        <div class="">
            <h4 class="heading">Certifications</h4>
                <div>
                    <ul>
                        <li>Professional Engineer - Florida</li>
                        <li>Qualified FDEP Stormwater Management Inspector</li>
                    </ul>
                    <!-- <p>Professional Engineer - Florida</p>
                    <p>Qualified FDEP Stormwater Management Inspector</p> -->
                </div>
        </div>


        <div class="hobbies">
            <h4 class="heading">Hobbies</h4>
            <span class="hobby"><fa-icon icon="child"></fa-icon>Family Time</span>
            <span class="hobby"><fa-icon icon="running"></fa-icon>Running</span> 
            <span class="hobby"><fa-icon icon="biking"></fa-icon>Fitness Instructor</span>
            <span class="hobby"><fa-icon icon="music"></fa-icon>Music</span>
            <span class="hobby"><fa-icon icon="cloud-sun"></fa-icon>Outdoors</span>
            <span class="hobby"><fa-icon icon="glasses"></fa-icon>Reading</span>
            <span class="hobby"><fa-icon icon="anchor"></fa-icon>Boating</span>
            <span class="hobby"><fa-icon icon="code-branch"></fa-icon>Constantly learning</span>  

        </div>



        
    </div>
    
</template>

<style lang="scss">
    .contact-me {
        cursor: pointer;

        &:hover {
            color: #ccc;
        }
    }
</style>


<script>

    export default {
        name: 'bio',

        methods: {
            showContactForm() {
                this.$bvModal.show('contact-me')
            }
        }


    }

</script>