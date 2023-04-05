# eBot_mac_x

    
    # Introduction 
    
        Every geek fond of iron-man and mostly inspired by jarvis technology. However Jarvis have very board specturm. Jarvis will control through voice over during flight mode, expand knowledge , chat with bots, summerize news, forsenic diaster sities etc. However, We are build small version of jarvis called mac_x. Currently mac_x perform basic terminals tasks such as open directory, write directory , create and so on.
        Mac_x have additional tasks such as chit chat with bot, question & answers with bot, expand knowledge by generating text. Future we will added many more features in our lists which are voice commands , online gerenative AI and so on. Minimum fees will be charged for our subcribers $ 396 per annual. 


    # Warning

        There may be possible that bots outperform in generative tasks in some cases. Both man and machines make mistakes, some are fatal and some are not. Don't relay on just generative solution , instead research 
        on problem.


    # Requirements
    [Processor minimum = Intel® Core™ i5-4690K CPU @ 3.50 GHz × 4], , [benchmark ~ 30 minutes],
    [RAM = 8 - 16GIB], [os = Linux Ubuntu-Lite-18.04]; 

    Libtorch is esstenial for ebot project. Different machines have different settings mac, linux, window.


    # Linux

        export LIBTORCH=/model/libtorch-cxx11-abi-shared-with-deps-1.13.1+cu117/libtorch
        export LD_LIBRARY_PATH=model/libtorch-cxx11-abi-shared-with-deps-1.13.1+cu117/libtorch/lib:$LD_LIBRARY_PATH

    # Other_machine

        https://github.com/guillaume-be/rust-bert


    # Build && Run 

        $ cargo build --release && cargo run

        [Error then reinstall]

                sudo apt install pkg-config
              
                sudo apt install libssl-dev

        After that

        $ cargo build --release && cargo run

    # Project Command Line Interface CLI

        Mac_X is an Bot interface. Advance features are also added crate over the time. 

            Open Commands :   [ cat | ls -a | cd ]
            Write Command :   [ -w  ]
            Version Command : [ -v | --v ]
            Create Command :  [ -c | --c ]
            Help Command :    [ ? ]
            Pricing Command : [ pricing ]
            Language Generation  : [ text  | --g ]
            Conversation with bot : [ text | --d ]
            Questioniare with bot : [ nlp | --q  ]
            version               : [ -v | --v   ]

    # How to run Mac_X Application 

        Linux 

            Fork Method 
            1. Fork the Project on github repositry.
            2. Download codebase or source code.
            3. Open terminal type ctrl + T , path your downloaded project. 

                ~/Download/ebot/mac_x $


            4. Cargo run on your terminal and play around.
            5. Send Invoice 
            6. Add your views 

    # Documentation :

         ~/Download/ebot/mac_x $ cargo doc --open

         This command open documentation of a project. Definitions, structures, enumerators and modules. User view docs in html format.


    # Licence = Mozilla Public Licence                


  

