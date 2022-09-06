<script>
    
</script>

<style lang="scss">

    .wrapper{
        display: flex;
        flex-direction: row;
        justify-content:space-between;

        .ads{
            height: 100vh;
            width: 25%;
            background-color: gray;
        }

        .content{
            text-align: center;
            display: flex;
            flex-direction: column;
            height: 100vh;
            align-items: center;

            h1{
                font-size: 10rem;
                margin: 2rem 0rem;
                line-height: 0.8;

                span{
                    font-size: 15rem;
                }
            }

            p{
                margin: 0.5rem 0rem;
                font-size:0.9rem;
            }


            button{
                font-family:  'Poppins', sans-serif;
                padding: 1rem 3rem;
                font-size: 2rem;
                box-shadow: rgba(50, 50, 93, 0.25) 0px 13px 27px -5px, rgba(0, 0, 0, 0.3) 0px 8px 16px -8px;
                background-color: white;
                margin: 2rem;
                border: 1px solid black;
                transition: 500ms;
                cursor: pointer;
            }

            button:hover{
                border-radius: 50px;
                background-color: black;
                color: white;
            }
        }
    }

    .footer{
        background-color: black;
        position: fixed;
        bottom: 0;
        color: white;
        width: 100%;
        margin: 0;
        text-align: center;
        font-weight: 200;

    }
</style>


<div class="wrapper">

    <div class="ads"></div>

    <div class="content">
        <h1>
            SHARE <br> <span>THIS </span>
        </h1>

        <p>We always share tons of things online, but most of them are useless.</p>
        <p>So I built this to make every share <b>count</b>.</p>
        <p>This is how it works: <br> All the revenue from these ads you're seeing it's going to the ONLUS <br> "Save the children" after we reach the goal of 10.000€.</p>

        <p>So yeah, please share this</p>

        <button> Share </button>
    </div>

    <div class="ads"></div>

</div>


<p class="footer"> P.S: The donations documents will be posted here.</p>