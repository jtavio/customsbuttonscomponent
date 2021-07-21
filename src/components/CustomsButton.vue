<template>
    <div>
        <h1>
            Buttons
        </h1>
        <div class="d-flex">
            <div class="mr-5">
                <p>{{buttons.title1}}</p>
                <button class="btn">Default</button>
            </div>
            <div class="mr-5">
                <p>{{buttons.titlehofc}}</p>
                <button class="btn btn-hover-focus">Default</button>
            </div>
            <div class="mr-5">
                <p>{{buttons.title5}}</p>
                <button disabled class="btn btn-cursor">Default</button>
            </div>
        </div>
        <div class="d-flex mt-5">
            <div class="mr-5">
                <p>{{buttons.title2}}</p>
                <button class="btn btn-outline">Default</button>
            </div>
            <div >
                <p>{{buttons.titlehofc}}</p>
                <button class="btn btn-outline btn2-hover-focus">Default</button>
            </div>
        </div>
        <div class="d-flex mt-5">
            <div class="mr-5">
                <p>{{buttons.title3}}</p>
                <button class="btn btn-text">Default</button>
            </div>
            <div class="mr-5">
                <p>{{buttons.titlehofc}}</p>
                <button class="btn btn-text btn3-hover-focus">Default</button>
            </div>
            <div class="mr-5">
                <p>{{buttons.title6}}</p>
                <button disabled class="btn btn-text btn-text-color">Disabled</button>
            </div>
        </div>
        <div class="d-flex mt-5">
            <div class="mr-5">
                <p>{{buttons.title4}}</p>
                <button class="btn btn-disable-shadow">Default</button>
            </div>
           
        </div>
        <div class="d-flex mt-5">
            <div class="mr-5">
                <p>{{buttons.title7}}</p>
                <button class="btn btn-disable-shadow">
                     <span class="material-icons mr-1">
                    accessibility
                    </span>
                    Default</button>
            </div>
            <div>
                <p>{{buttons.title8}}</p>
                <button class="btn btn-disable-shadow">Default 
                    <span class="material-icons ml-1">
                    accessibility
                    </span>
                </button>
            </div>
        </div>
        <div class="d-flex mt-5">
            <div class="mr-5">
                <p>{{buttons.title9}}</p>
                <button class="btn btn-sm btn-disable-shadow">
                    Default</button>
            </div>
            <div class="mr-5">
                <p>{{buttons.title10}}</p>
                <button class="btn btn-disable-shadow">Default 
                </button>
            </div>
            <div class="mr-5">
                <p>{{buttons.title11}}</p>
                <button class="btn btn-lg btn-disable-shadow">Default 
                </button>
            </div>
        </div>
        <div class="d-flex mt-5">
            <div class="mr-5">
                <p>{{buttons.title12}}</p>
                <button class="btn">
                    Default</button>
            </div>
            <div class="mr-5">
                <p>{{buttons.title13}}</p>
                <button class="btn btn-disable-shadow">Default 
                </button>
            </div>
            <div class="mr-5">
                <p>{{buttons.title14}}</p>
                <button class="btn btn-secundary">Secundary 
                </button>
            </div>
            <div class="mr-5">
                <p>{{buttons.title15}}</p>
                <button class="btn btn-danger">Danger 
                </button>
            </div>
        </div>
        <div class="d-flex mt-5 align-it">
                <div class="mr-5" >
                    <p >{{buttons.titlehofc}}</p>
                    <button class="btn btn-hover-focus">
                        Default</button>
                </div>

            <div class="mr-5">
                <p></p>
                <button class="btn btn-disable-shadow btn3-hover-focus">Default 
                </button>
            </div>
            <div class="mr-5">
                
                <button class="btn btn-secundary btn-secundary-hover-focus">Secundary 
                </button>
            </div>
            <div class="mr-5">
                
                <button class="btn btn-danger btn-danger-hover-focus">Danger 
                </button>
            </div>
        </div>

        <p class="text-opacity">create by Jonathan T. - devChallenges.io</p>
    </div>
</template>

<script>
export default {
    name:"CustomsButton",
    data(){
        return {
            buttons:{
                title1: '<Button />',
                titlehofc: '&:hover, &:focus',
                title2: '<Button variant="outline" />',
                title3: '<Button variant="text" />',
                title4: '<Button disableShadow />',
                title5: '<Button disabled />',
                title6: '<Button variant="text" disabled />',
                title7: '<Button startIcon="accessibility" />',
                title8: '<Button endIcon="accessibility" />',
                title9: '<Button size="sm" />',
                title10: '<Button size="md" />',
                title11: '<Button size="lg" />',
                title12: '<Button color="default" />',
                title13: '<Button color="primary" />',
                title14: '<Button color="secondary" />',
                title15: '<Button color="danger" />',
            } 
        }
    }
}
</script>
<style scoped>

.material-icons {
  font-family: 'Material Icons';
  font-weight: normal;
  font-style: normal;
  font-size: 20px;  /* Preferred icon size */
  display: inline-block;
  line-height: 1;
  text-transform: none;
  letter-spacing: normal;
  word-wrap: normal;
  white-space: nowrap;
  direction: ltr;
  vertical-align: middle;
  

  /* Support for all WebKit browsers. */
  -webkit-font-smoothing: antialiased;
  /* Support for Safari and Chrome. */
  text-rendering: optimizeLegibility;

  /* Support for Firefox. */
  -moz-osx-font-smoothing: grayscale;

  /* Support for IE. */
  font-feature-settings: 'liga';
}

.text-opacity{
    color: #A9A9A9;
    font-weight: 700;
    margin-top: 20px;
}

.d-flex {
    display: flex;
}
.align-it{
    align-items: flex-end;
}
.mr-5{
    margin-right: 45px;
}
.mt-5{
    margin-top: 45px;
}
.ml-1{
    margin-left: 5px;
}
.mr-1{
    margin-right: 5px;
}
.btn{
    padding: 8px 16px;
    border-radius: 6px;
    background: #E0E0E0;
    border: none;
    box-shadow: 0px 2px 3px rgba(51, 51, 51, 0.2);
    cursor: pointer;
    font-size: 14px;
    font-weight: 500;
}
.btn-hover-focus:focus, .btn-hover-focus:hover{
    background-color: #AEAEAE;
}
.btn-outline {
    border: 1px solid #3D5AFE;
    background-color: #FFF;
    color:#3D5AFE
}
.btn2-hover-focus:hover, .btn2-hover-focus:focus{
    background: rgba(41, 98, 255, 0.1);
}

.btn-text{
    border: none;
    background-color: #fff;
    box-shadow:none;
    color:#3D5AFE;
}
.btn3-hover-focus:hover, .btn3-hover-focus:focus{
    background: rgba(41, 98, 255, 0.1);
}
.btn-disable-shadow{
    background-color: #3D5AFE;
    color:#FFF;
}
.btn-cursor{
    cursor: default;
}
.btn-text-color{
    color: #9E9E9E;
}
.btn-sm{
    padding: 6px 12px;
}
.btn-lg{
    padding: 11px 22px;
}

.btn-secundary{
    background-color: #455A64;
    color: #FFFFFF;
}

.btn-danger {
    background-color: #D32F2F;
    color: #FFFFFF;
}

.btn3-hover-focus:hover, .btn3-hover-focus:focus{
    background-color: #0039CB;
}
.btn-secundary-hover-focus:hover, .btn-secundary-hover-focus:focus{
    background-color:#1C313A;
}
.btn-danger-hover-focus:hover, .btn-danger-hover-focus:focus{
    background-color:#9A0007;
}

</style>