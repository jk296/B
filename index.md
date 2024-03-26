---
title: J.
header_type: base
subtitle: Listen & Learn
---

<head>
<!-- <meta name="viewport" content="width=device-width, height=device-height, initial-scale=0.50, minimum-scale=0.50"> -->
 	 

	<meta charset="UTF-8">
    <title></title>

    <!-- Include Amplitude JS -->
    <script type="text/javascript" src="https://cdn.jsdelivr.net/npm/amplitudejs@5.2.1/dist/amplitude.min.js"></script>

    <!-- Include Style Sheet -->
    <link rel="stylesheet" type="text/css" href="css/app.css" />
</head>
<body>
    <!-- Blue Playlist Container -->
    <div id="blue-playlist-container">

        <!-- Amplitude Player -->
        <div id="amplitude-player">

            <!-- Left Side Player -->
            <div id="amplitude-left">
                <img data-amplitude-song-info="cover_art_url" />
                <div id="player-left-bottom">
                    <div id="time-container">
                        <span class="current-time">
                            <span class="amplitude-current-minutes"></span>:<span class="amplitude-current-seconds"></span>
                        </span>
                        <div id="progress-container">
                            <input type="range" class="amplitude-song-slider" />
                            <progress id="song-played-progress" class="amplitude-song-played-progress"></progress>
                            <progress id="song-buffered-progress" class="amplitude-buffered-progress" value="0"></progress>
                        </div>
                        <span class="duration">
                            <span class="amplitude-duration-minutes"></span>:<span class="amplitude-duration-seconds"></span>
                        </span>
                    </div>

                    <div id="control-container">
                        <div id="repeat-container">
                            <div class="amplitude-repeat" id="repeat"></div>
                            <div class="amplitude-shuffle amplitude-shuffle-off" id="shuffle"></div>
                        </div>

                        <div id="central-control-container">
                            <div id="central-controls">
                                <div class="amplitude-prev" id="previous"></div>
                                <div class="amplitude-play-pause" id="play-pause"></div>
                                <div class="amplitude-next" id="next"></div>
                            </div>
                        </div>

                        <div id="volume-container">
                            <div class="volume-controls">
                                <div class="amplitude-mute amplitude-not-muted"></div>
                                <input type="range" class="amplitude-volume-slider" />
                                <div class="ms-range-fix"></div>
                            </div>
                            <div class="amplitude-shuffle amplitude-shuffle-off" id="shuffle-right"></div>
                        </div>
                    </div>

                    <div id="meta-container">
                        <span data-amplitude-song-info="name" class="song-name"></span>

                        <div class="song-artist-album">
                            <span data-amplitude-song-info="artist"></span>
                            <span data-amplitude-song-info="album"></span>
                        </div>
                    </div>
                </div>
            </div>
            <!-- End Left Side Player -->
            <!-- Right Side Player -->
            <div id="amplitude-right">
                <div class="song amplitude-song-container amplitude-play-pause" data-amplitude-song-index="0">
                    <div class="song-now-playing-icon-container">
                        <div class="play-button-container">

                        </div>
                        <img class="now-playing" src="./img/now-playing.svg" height="30px" />
                    </div>
                    <div class="song-meta-data">
                        <span class="song-title">Alright, I won't argue with you anymore. You have the final word.</span>
                        <span class="song-artist">好啦，我不要再跟你吵了。你說了算。</span>
                    </div>

                    <span class="song-duration">0:03</span>
                </div>
                <div class="song amplitude-song-container amplitude-play-pause" data-amplitude-song-index="1">
                    <div class="song-now-playing-icon-container">
                        <div class="play-button-container">

                        </div>
                        <img class="now-playing" src="./img/now-playing.svg" height="30px" />
                    </div>
                    <div class="song-meta-data">
                        <span class="song-title">This game-changing product is a quantum leap for us.</span>
                        <span class="song-artist">這個顛覆性產品對我們來說是一項創舉。</span>
                    </div>

                    <span class="song-duration">0:03</span>
                </div>
                <div class="song amplitude-song-container amplitude-play-pause" data-amplitude-song-index="2">
                    <div class="song-now-playing-icon-container">
                        <div class="play-button-container">

                        </div>
                        <img class="now-playing" src="./img/now-playing.svg" height="30px" />
                    </div>
                    <div class="song-meta-data">
                        <span class="song-title">She is a philanthropist with a big heart. I admire her a lot.</span>
                        <span class="song-artist">她是個心胸寬大的慈善家。我非常仰慕她。</span>
                    </div>

                    <span class="song-duration">0:04</span>
                </div>
                <div class="song amplitude-song-container amplitude-play-pause" data-amplitude-song-index="3">
                    <div class="song-now-playing-icon-container">
                        <div class="play-button-container">

                        </div>
                        <img class="now-playing" src="./img/now-playing.svg" height="30px" />
                    </div>
                    <div class="song-meta-data">
                        <span class="song-title">We decided to zero in on our core business.</span>
                        <span class="song-artist">我們決定要專注於核心事業。</span>
                    </div>

                    <span class="song-duration">0:03</span>
                </div>
                <div class="song amplitude-song-container amplitude-play-pause" data-amplitude-song-index="4">
                    <div class="song-now-playing-icon-container">
                        <div class="play-button-container">

                        </div>
                        <img class="now-playing" src="./img/now-playing.svg" height="30px" />
                    </div>
                    <div class="song-meta-data">
                        <span class="song-title">Don't let them drag your name through the mud.</span>
                        <span class="song-artist">不要讓他們抹黑你。</span>
                    </div>

                    <span class="song-duration">0:02</span>
                </div>
                <div class="song amplitude-song-container amplitude-play-pause" data-amplitude-song-index="5">
                    <div class="song-now-playing-icon-container">
                        <div class="play-button-container">

                        </div>
                        <img class="now-playing" src="./img/now-playing.svg" height="30px" />
                    </div>
                    <div class="song-meta-data">
                        <span class="song-title">Believe in yourself. A positive attitude will go a long way.</span>
                        <span class="song-artist">相信你自己。正面樂觀的心態對你會有莫大的幫助。</span>
                    </div>

                    <span class="song-duration">0:04</span>
                </div>
                <div class="song amplitude-song-container amplitude-play-pause" data-amplitude-song-index="6">
                    <div class="song-now-playing-icon-container">
                        <div class="play-button-container">

                        </div>
                        <img class="now-playing" src="./img/now-playing.svg" height="30px" />
                    </div>
                    <div class="song-meta-data">
                        <span class="song-title">With her in the equation, the project will definitely go ahead smoothly.</span>
                        <span class="song-artist">有了她的加入，計劃一定會順利進行。</span>
                    </div>

                    <span class="song-duration">0:05</span>
                </div>
                <div class="song amplitude-song-container amplitude-play-pause" data-amplitude-song-index="7">
                    <div class="song-now-playing-icon-container">
                        <div class="play-button-container">

                        </div>
                        <img class="now-playing" src="./img/now-playing.svg" height="30px" />
                    </div>
                    <div class="song-meta-data">
                        <span class="song-title">Although I don't know what lies ahead, I have a good feeling about this year.</span>
                        <span class="song-artist">雖然我不知道未來會發生什麼事，但我覺得今年會有好事發生。</span>
                    </div>

                    <span class="song-duration">0:04</span>
                </div>
                <div class="song amplitude-song-container amplitude-play-pause" data-amplitude-song-index="8">
                    <div class="song-now-playing-icon-container">
                        <div class="play-button-container">

                        </div>
                        <img class="now-playing" src="./img/now-playing.svg" height="30px" />
                    </div>
                    <div class="song-meta-data">
                        <span class="song-title">If you ask me, our chance of losing the bid is wafer-thin.</span>
                        <span class="song-artist">要我說的話，我們競標失利的可能性微乎其微。</span>
                    </div>

                    <span class="song-duration">0:04</span>
                </div>
                <div class="song amplitude-song-container amplitude-play-pause" data-amplitude-song-index="9">
                    <div class="song-now-playing-icon-container">
                        <div class="play-button-container">

                        </div>
                        <img class="now-playing" src="./img/now-playing.svg" height="30px" />
                    </div>
                    <div class="song-meta-data">
                        <span class="song-title">You don't need to name-drop to convince people how brilliant you are.</span>
                        <span class="song-artist">你不需要靠打著大人物的名號來說服別人你有多優秀。</span>
                    </div>

                    <span class="song-duration">0:03</span>
                </div>
                <div class="song amplitude-song-container amplitude-play-pause" data-amplitude-song-index="10">
                    <div class="song-now-playing-icon-container">
                        <div class="play-button-container">

                        </div>
                        <img class="now-playing" src="./img/now-playing.svg" height="30px" />
                    </div>
                    <div class="song-meta-data">
                        <span class="song-title">I don't want to back-pedal on my stance just to fit in.</span>
                        <span class="song-artist">我不想要為了融入大家就改變我的立場。</span>
                    </div>

                    <span class="song-duration">0:02</span>
                </div>
                <div class="song amplitude-song-container amplitude-play-pause" data-amplitude-song-index="11">
                    <div class="song-now-playing-icon-container">
                        <div class="play-button-container">

                        </div>
                        <img class="now-playing" src="./img/now-playing.svg" height="30px" />
                    </div>
                    <div class="song-meta-data">
                        <span class="song-title">It's a highly sought-after skill so you'll be able to pick and choose where you work.</span>
                        <span class="song-artist">這是非常搶手的技能，所以你可以挑選你要在哪裡工作。</span>
                    </div>

                    <span class="song-duration">0:04</span>
                </div>
                <div class="song amplitude-song-container amplitude-play-pause" data-amplitude-song-index="12">
                    <div class="song-now-playing-icon-container">
                        <div class="play-button-container">

                        </div>
                        <img class="now-playing" src="./img/now-playing.svg" height="30px" />
                    </div>
                    <div class="song-meta-data">
                        <span class="song-title">Can you fill me in on the ins and outs of this technique?</span>
                        <span class="song-artist">你可以告訴我這個技術的細節嗎？</span>
                    </div>

                    <span class="song-duration">0:02</span>
                </div>
                <div class="song amplitude-song-container amplitude-play-pause" data-amplitude-song-index="13">
                    <div class="song-now-playing-icon-container">
                        <div class="play-button-container">

                        </div>
                        <img class="now-playing" src="./img/now-playing.svg" height="30px" />
                    </div>
                    <div class="song-meta-data">
                        <span class="song-title">The deal-breaker is their lack of flexibility in pricing.</span>
                        <span class="song-artist">交易破局的原因是他們在定價上缺乏彈性。</span>
                    </div>

                    <span class="song-duration">0:03</span>
                </div>
                <div class="song amplitude-song-container amplitude-play-pause" data-amplitude-song-index="14">
                    <div class="song-now-playing-icon-container">
                        <div class="play-button-container">

                        </div>
                        <img class="now-playing" src="./img/now-playing.svg" height="30px" />
                    </div>
                    <div class="song-meta-data">
                        <span class="song-title">She's an up-and-coming entrepreneur. I see a bright future ahead of her.</span>
                        <span class="song-artist">她是大有可為的創業家。在我看來，她前途一片光明。</span>
                    </div>

                    <span class="song-duration">0:03</span>
                </div>
                <div class="song amplitude-song-container amplitude-play-pause" data-amplitude-song-index="15">
                    <div class="song-now-playing-icon-container">
                        <div class="play-button-container">

                        </div>
                        <img class="now-playing" src="./img/now-playing.svg" height="30px" />
                    </div>
                    <div class="song-meta-data">
                        <span class="song-title">Do you want me to spell out the procedure step by step for you?</span>
                        <span class="song-artist">你要我把流程一個步驟一個步驟詳細解釋給你聽嗎？</span>
                    </div>

                    <span class="song-duration">0:03</span>
                </div>
                <div class="song amplitude-song-container amplitude-play-pause" data-amplitude-song-index="16">
                    <div class="song-now-playing-icon-container">
                        <div class="play-button-container">

                        </div>
                        <img class="now-playing" src="./img/now-playing.svg" height="30px" />
                    </div>
                    <div class="song-meta-data">
                        <span class="song-title">Bricks-and-mortar stores are still going strong in our industry.</span>
                        <span class="song-artist">實體店在我們這個行業還是蒸蒸日上。</span>
                    </div>

                    <span class="song-duration">0:03</span>
                </div>
                <div class="song amplitude-song-container amplitude-play-pause" data-amplitude-song-index="17">
                    <div class="song-now-playing-icon-container">
                        <div class="play-button-container">

                        </div>
                        <img class="now-playing" src="./img/now-playing.svg" height="30px" />
                    </div>
                    <div class="song-meta-data">
                        <span class="song-title">I'd like to thank all the unsung heroes and heroines behind this success.</span>
                        <span class="song-artist">我想要感謝這次成功背後所有的無名英雄和女英雄。</span>
                    </div>

                    <span class="song-duration">0:05</span>
                </div>
                <div class="song amplitude-song-container amplitude-play-pause" data-amplitude-song-index="18">
                    <div class="song-now-playing-icon-container">
                        <div class="play-button-container">

                        </div>
                        <img class="now-playing" src="./img/now-playing.svg" height="30px" />
                    </div>
                    <div class="song-meta-data">
                        <span class="song-title">Ignore him. He's such a Monday-morning quarterback.</span>
                        <span class="song-artist">別理他。他只會事後出一張嘴批評。</span>
                    </div>

                    <span class="song-duration">0:03</span>
                </div>
                <div class="song amplitude-song-container amplitude-play-pause" data-amplitude-song-index="19">
                    <div class="song-now-playing-icon-container">
                        <div class="play-button-container">

                        </div>
                        <img class="now-playing" src="./img/now-playing.svg" height="30px" />
                    </div>
                    <div class="song-meta-data">
                        <span class="song-title">You should touch on your customers' pain points in the abstract.</span>
                        <span class="song-artist">你應該要在摘要裡稍微提到顧客的痛點。</span>
                    </div>

                    <span class="song-duration">0:03</span>
                </div>
                <div class="song amplitude-song-container amplitude-play-pause" data-amplitude-song-index="20">
                    <div class="song-now-playing-icon-container">
                        <div class="play-button-container">

                        </div>
                        <img class="now-playing" src="./img/now-playing.svg" height="30px" />
                    </div>
                    <div class="song-meta-data">
                        <span class="song-title">I will bring my A-game to the team!</span>
                        <span class="song-artist">我在團隊會全力以赴！</span>
                    </div>

                    <span class="song-duration">0:02</span>
                </div>




            </div>
            <!-- End Right Side Player -->
        </div>
        <!-- End Amplitdue Player -->
    </div>

    <!--
        Include UX functions JS

        NOTE: These are for handling things outside of the scope of AmplitudeJS
    -->
    <script type="text/javascript" src="js/functions.js"></script>

    <center>
        <br><br><br><br><br><br><br>
	<text style="font-size:18px">
            Updated 26 March 2025
        </text>

