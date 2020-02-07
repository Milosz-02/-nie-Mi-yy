//CONFIG [nie]Miłyy
//AktUALIZACJA 02.02.2020 
//JEŻELI PLIK TEN NIE ZADZIAŁA STWÓRZ NOWY PLIK CFG, SKOPIUJ TEN I WKLEJ GO DO UTWORZONEGO PLIKU

//USTAWIENIA MYSZKI 
//(DPI 400 | HZ 1000, Windows 6/11 | Precyzja WYŁĄCZONA)

m_rawinput                        "1"         // Włącza bezpośredni odczyt z myszki. (Ustawienia Windowsa nie wpływają na myszkę.)
sensitivity                       "1.4"       // Czułość myszki.
zoom_sensitivity_ratio_mouse      "1.1"       // Czułość myszki podczas przybliżenia
m_customaccel                     "0"         // Całkowicie wyłącza akceleracje myszy.


//USTAWIENIA DŹWIEKU
//voice_loopback                  "1"         // Użyj tej komendy, jeśli chcesz sprawdzić jak Twój mikrofon brzmi w grze.

volume                            "1"         // Ogólna głośność gry.
snd_menumusic_volume              "0.01"      // Głośnosc muzyki w menu.
snd_roundstart_volume             "0.01"      // Wyłączenie muzyki na początku rundy.
nd_roundend_volume                "0.01"      // Wyłączenie muzyki na końcu rundy.
snd_mapobjective_volume           "0.01"      // Wyłączenie muzyki po podlożeniu bomby.
snd_tensecondwarning_volume       "0.15"      // Włączenie muzyki, gdy do wybuchu bomby zostanie 10 sekund.
snd_deathcamera_volume            "0.3"       // Wyłączenie muzyki podczas zgonu.
snd_mix_async                     "1"         // Usprawnia działanie komendy snd_mixahead.
snd_mixahead                      "0.025"     // Ustala opóźnienie dźwięku. Możesz pokusić się o niższą wartość kosztem FPS. np. 0.010.
voice_scale                       "0.4"       // Głośność komunikacji głosowej na 70%,


//HUD

cl_hud_background_alpha           "0.5"       // Ustala przeźroczystość tła hudu
cl_hud_bomb_under_radar           "1"
cl_hud_color                      "1"         // Zmienia kolor hudu.
cl_hud_healthammo_style           "0"
cl_hud_playercount_pos            "0"
cl_hud_playercount_showcount      "0"
cl_hud_radar_scale                "1"         // Powiększa radar
hud_scaling                       "0.853769"  // Skala hudu 
hud_showtargetid                  "1"         // Wyświetlanie nicku przeciwnika na którego namierzyamy.
hud_takesshots                    "0"
cl_radar_always_centered          "1"
cl_radar_icon_scale_min           "0.6"
cl_radar_rotate                   "1"
cl_radar_scale                    "0.500000"  // Skala mapy na radarze.
cl_radar_square_with_scoreboard   "1"         // Radar zmienia się w kwadrat podczas włączonego TAB.
cl_radar_always_centered          "1"         // Wyłącza czarne tło wokół radaru, dzięki temu więcej widać na mapie.
cl_radar_icon_scale_min           "0.6"       // Wielkość ikonek graczy na radarze.
cl_radar_rotate                   "1"         // Włącza obracanie się radaru.
cl_radar_scale                    "0.500000"
cl_radar_square_with_scoreboard   "1"
net_graph                         "1"
net_graphpos                      "180"
net_graphproportionalfont         "0"


//USTAWIENIA OBRAZU

ROZDZIELCZOŚĆ 1600X900
PROPORCJA EKRANU 16X9


//VIEVMODEL
 
cl_viewmodel_shift_left_amt       "1.5"
cl_viewmodel_shift_right_amt      "0.75"
viewmodel_fov                     "60"
viewmodel_offset_x                "1.300000"  // Pozycja broni prawo/lewo
viewmodel_offset_y                "1"         // Pozycja broni przód/tył   
viewmodel_offset_z                "-1.500000" // Pozycja broni góra/dół
viewmodel_recoil                  "0"         // Wyłącza odskakiwanie broni podczas strzelania
viewmodel_presetpos               "0"
cl_bobamt_lat                     "0.1"       // Zmniejsza poziom trzesienia sie celownika w awp/scout.
cl_bobamt_vert                    "0.1"       // Zmniejsza poziom trzesienia sie celownika w awp/scout.
cl_bobcycle                       "0.1"       // Minimalne trzesienie sie broni.
cl_bob_lower_amt                  "0.1"       // Minimalne trzesienie sie broni.


//ŁĄCZE i SERWERY

=rate                             "125000"
cl_updaterate                     "64"
cl_cmdrate                        "64"
=cl_interp                        "0"
=cl_interp_ratio                  "2.0"
cl_timeout                        "999"       // Długość timeoutu
cl_resend                         "2"         // Po jakim czasie na ponawiać połączenie z serwerem w przypadku utraty połączenia. (Czas w sekundach - Standardowo 6 sekund).
cl_resend_timeout                 "30"        // Czas przez jaki będzie następowało auto dołączanie do serwera po ustracie połączenia.


// USTAWIENIA NET GRAPH

net_graph                         "1"         // 1 - Włącza net graph - pokazywanie fps, pingu, tickrate itd. Używam 0, gdyż korzystam z binda na wyświetlanie netgraphu pod TAB.
net_graphpos                      "180"       // Pozycja net graph.
net_graphproportionalfont         "0"         // Zmniejszenie czcionki w net graph.

 
// SERWERY VALVE


mm_dedicated_search_maxping       "70"        // Maksymalny ping na MM podczas wyszukiwania meczu.
cl_color                          "4"         // Preferowany kolor gracza na turniejowym. 0 - żólty, 1 - fioletowy, 2 - zielony, 3 - niebieski, 4 - pomarańczowy.


// INNE KOMENDY


engine_no_focus_sleep             "0"         // Wyłącza tryb uśpienia gry, gdy jest zminimalizowana. Komenda przyjazna streamerom.
cl_teamid_overhead_mode           "2"         // Włącza pokazywanie nicków członków drużyny przez ściany.
cl_use_opens_buy_menu             "0"         // Wyłącza możliwość kupowania broni przyciskiem E (+use) Dzięki temu można podnieść broń na spawnie.
cl_forcepreload                   "0"         // Włącza/Wyłącza force preload. Lepiej zostawić na 0, włączenie tej funkcji może sprawić przycinki gry.
cl_show_clan_in_death_notice      "0"         // Wyłączenie pokazywania nazwy klanu. (Tam gdzie się wyświetla kto kogo zabił.
func_break_max_pieces             "0"         // Wyłączenie odpadków po rozwalonych elementatch na mapie.


developer 1
con_filter_enable 2
con_filter_text_out "Player:"                 //DAMAGE SKRYPT
con_filter_text "damage Given"


//BINDY


alias "+jumpthrow2" "+jump;-attack;-attack2"
alias "-jumpthrow2" "-jump"                   // SKAKANIE+RZUCANIE
bind "alt" "+jumpthrow2"


alias +DJUMP "+jump; +duck"
alias -DJUMP "-JUMP; -DUCK"                   // SKOK+KUCANIE
bind "space" "+DJUMP"


bind "MWHEELUP" "+jump"                       // SKOK NA SCROLLU
bind "MWHEELDOWN" "+jump"


bind "C" "r_cleardecals"                      // CZYSZCZENIE MAPY
bind "P" "noclip"                             // Latanie po mapie podczas ćwieczenia.
bind "V" "weapon_smokegrenade"      
bind "*" "clutch_mode_toggle"                 // CLUTCH BIND - Wycisza/Odcisza graczy
bind "*" "clutch_mode_toggle"                 // CLUTCH BIND - Wycisza/Odcisza graczy


bind rightarrow +right                        //OBRACANIE SIĘ NA STRZAŁKACH
bind leftarrow +left 

bind ","  say ¯\_(ツ)_/¯"

alias "+shh" "incrementvar volume 0 1 0.05;+speed"
alias "-shh" "incrementvar volume 0 1 -0.05;-speed"   // VOLUME UP PODCZAS CICHEGO CHODZENIA   
bind "shift" "+shh"                           


//TRENING


bind "KP_ENTER" "record record.record; ent_fire smokegrenade_projectile kill; stop"    //GASZENIE SMOKE


bind "KP_MINUS" "writeip; con_logfile cfg/banned_ip.log; getpos_exact; con_logfile 0"  //TELEPORT

bind "KP_PLUS" "exec banned_ip.log"           

bind "f5" "+przewijanie"
alias "+przewijanie" "host_timescale 4"   //PRZEWIJANIE
alias "-przewijanie" "host_timescale 1"


alias "trening1" "sv_cheats 1;mp_roundtime_defuse 60; mp_roundtime 60; bot_stop 1; bot_kick; mp_limitteams 5; mp_autoteambalance 0; mp_respawn_on_death_ct 1; mp_respawn_on_death_t 1; mp_warmup_end; mp_restartgame 1; mp_autokick 0"


alias "trening2" "impulse 101; sv_infinite_ammo 1; sv_grenade_trajectory 1; ammo_grenade_limit_total 5; mp_buytime 9999; mp_buy_anywhere 1 ;give weapon_smokegrenade; give weapon_molotov; give weapon_flashbang; give weapon_hegrenade"


alias "dmct" "sv_cheats 1; bot_kick; mp_roundtime 60; mp_limitteams 10; mp_autoteambalance 0; bot_add_ct; bot_add_ct; bot_add_ct; bot_add_ct; bot_add_ct; bot_add_ct; bot_add_ct; bot_add_ct; mp_restartgame 1"


alias "dmt" "sv_cheats 1; bot_kick; mp_roundtime 60; mp_limitteams 10; mp_autoteambalance 0; bot_add_t; bot_add_t; bot_add_t; bot_add_t; bot_add_t; bot_add_t; bot_add_t; bot_add_t; mp_restartgame 1"


alias "dc" "disconnect"
alias "rs" "mp_restartgame 1"
alias "wh1" "r_drawothermodels 2" 	
alias "wh0" "r_drawothermodels 1"
alias "qq"  "quit"


alias "bk" "bot_kick"
alias "bac" "bot_add_ct"
alias "bat" "bot_add_t"
alias "bs1" "bot_stop 1"
alias "bs0" "bot_stop 0"
alias "bp" "bot_place"
alias "bc1" "bot_crouch 1"
alias "bc0" "bot_crouch 0"
alias "bm1" "bot_mimic 1"
alias "bm0" "bot_mimic 0"


alias "mirage" "map de_mirage"
alias "nuke" "map de_nuke"
alias "aztec" "map de_aztec "
alias "cache" "map de_cache"
alias "cobble" "map de_cbble"
alias "dust" "map de_dust"
alias "dust2" "map de_dust2"
alias "inferno" "map de_inferno"
alias "overpass" "map de_overpass"
alias "season" "map de_season"
alias "train" "map de_tain"
alias "vertigo" "map de_vertigo"


host_writeconfig

