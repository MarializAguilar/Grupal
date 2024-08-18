        body{
            background-color: #F6F4F3;
            display: grid;
            grid-template-rows: 150px 350px 300px 300px;
            grid-template-columns: 40% 20% 20% 20%;
            grid-template-areas: "header header header header"
                                 "sec sec sec sec"
                                 "cua cin se sie"
                                 "footer footer footer footer"
        }

        header{
            background-color: #C2B2A0;
            display: grid;
            grid-area: header;
        }

        nav{
            background-color: #C2B2A0;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            align-items: center;
            margin: 10px;
        }

        aside{
            background-color: #C2B2A0;
            width: 150px;
            display: grid;
            margin: 10px;
            flex-grow: 3;
            color: #31241E;
        }

        #sec{
            background: url("https://www.opinion.com.bo/media/opinion/images/2018/12/02/2018N275129.jpg") no-repeat center;
            background-color: #F6F4F3;
            display: grid;
            grid-area: sec;
            margin: 10px;
            animation: fadeIn 2s;
        }

        article{            
            display: grid;
            margin: 10px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        #cua{
            background-color: #C2B2A0;
            grid-area: cua;
            color: #306044;
        }
       
        #cin{
            flex-wrap: wrap;
            background-color: #4D8464;
            grid-area: cin;
            color: #D1C8C1;
        }
       
        #se{
            flex-wrap: wrap;
            background-color: #C2B2A0;
            grid-area: se;
            color: #306044;
        }
       
        #sie{
            flex-wrap: wrap;
            background-color: #4D8464;
            grid-area: sie;
            color: #D1C8C1;
        }

        footer{
            background-color: #C2B2A0;
            display: grid;
            grid-area: footer;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #31241E;
            padding: 20px;
        }

        .fi{
            font-family: Arial, sans-serif;
            text-align: center;
            font-size: 20px;
            font-weight: bold;
            margin: 10px;
        }
        
        a{
            color: #31241E;
            font-family: Arial, sans-serif;
            text-align: center;
            font-size: 18px;
            font-weight: bold;
            text-decoration: none;
        }

        a:hover{
            color: #86654B;
        }

        #logo {
            height: 40px;
            width: auto;
            margin: 0 10px;
        }

        img{
            width: 250px;
            animation: fadeIn 2s;
        }

        .conte{
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-bottom: 20px;
        }

        .social{
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .social a{
            margin: 0 10px;
        }

        .social img{
            width: 50px;
        }

        @media (max-width: 1400px) {
            body{
            background-color: #F6F4F3;
            display: grid;
            grid-template-rows: 200px 300px 200px 300px 300px 300px 400px;
            grid-template-columns: 100%;
            grid-template-areas: "header"
                                 "sec"
                                 "cua"
                                 "cin"
                                 "se"
                                 "sie"
                                 "footer"
            }

            .in{
            font-size: 14px;
            }

            #logo {
                height: 40px;
                width: auto;
                margin: 0 10px;
            }

            img{
                width: 300px;
            }
        }

        @keyframes fadeIn{
            0%{
                opacity: 0;
                transform: scale(0.5);
            }

            100%{
                opacity: 1;
                transform: scale(1);
            }
        }
