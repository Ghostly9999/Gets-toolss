--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then local v86=0;while true do if (v86==0) then v19=v0(v3(v30,1,1));return "";end end else local v87=v2(v0(v30,16));if v19 then local v110=0;local v111;while true do if (v110==1) then return v111;end if (v110==0) then v111=v5(v87,v19);v19=nil;v110=1;end end else return v87;end end end);local function v20(v31,v32,v33) if v33 then local v88=(v31/((929 -(214 + 713))^(v32-(1 + 0))))%((5 -3)^(((v33-((1 + 1) -1)) -(v32-(1 -0))) + (2 -1))) ;return v88-(v88%(620 -(544 + 11 + 64))) ;else local v89=((2024 -(892 + 65)) -(68 + 997))^(v32-(932 -(857 + 74))) ;return (((v31%(v89 + v89))>=v89) and (569 -(367 + (479 -278)))) or (117 -(32 + 85)) ;end end local function v21() local v34=v1(v16,v18,v18);v18=v18 + 1 ;return v34;end local function v22() local v35=0 -0 ;local v36;local v37;while true do if (v35==(1 -0)) then return (v37 * (606 -(87 + (1045 -782)))) + v36 ;end if (v35==(180 -(67 + 113))) then v36,v37=v1(v16,v18,v18 + 2 + 0 );v18=v18 + (4 -2) ;v35=1 + 0 ;end end end local function v23() local v38,v39,v40,v41=v1(v16,v18,v18 + (955 -(802 + (1147 -(915 + 82)))) );v18=v18 + (10 -(16 -10)) ;return (v41 * (30433252 -13656036)) + (v40 * (38178 + 27358)) + (v39 * (187 + 69)) + v38 ;end local function v24() local v42=v23();local v43=v23();local v44=1;local v45=(v20(v43,1,20) * ((2 -0)^(1219 -(1069 + 118)))) + v42 ;local v46=v20(v43,47 -26 ,67 -36 );local v47=((v20(v43,6 + 26 )==(1 -0)) and  -(1 + 0)) or ((2278 -(998 + 488)) -(368 + 423)) ;if (v46==((0 + 0) -0)) then if (v45==(18 -(10 + 7 + 1))) then return v47 * 0 ;else v46=3 -(774 -(201 + 571)) ;v44=442 -(416 + 26) ;end elseif (v46==(6535 -(5626 -(116 + 1022)))) then return ((v45==((0 -0) + 0)) and (v47 * (1/(0 -0)))) or (v47 * NaN) ;end return v8(v47,v46-((858 + 603) -(145 + 293)) ) * (v44 + (v45/((432 -(44 + 386))^52))) ;end local function v25(v48) local v49;if  not v48 then local v90=0 -0 ;while true do if (v90==(0 -0)) then v48=v23();if (v48==(859 -(814 + 45))) then return "";end break;end end end v49=v3(v16,v18,(v18 + v48) -(2 -1) );v18=v18 + v48 ;local v50={};for v66=1, #v49 do v50[v66]=v2(v1(v3(v49,v66,v66)));end return v6(v50);end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v51=(function() return function(v91,v92,v93,v94,v95,v96,v97,v98) local v91=(function() return 0;end)();local v92=(function() return;end)();local v93=(function() return;end)();while true do if (v91== #",") then if (v92== #"|") then v93=(function() return v94()~=(1695 -(1229 + 466)) ;end)();elseif (v92==2) then v93=(function() return v95();end)();elseif (v92== #"xnx") then v93=(function() return v96();end)();end v97[v98]=(function() return v93;end)();break;end if (v91==0) then local v117=(function() return 578 -(386 + 192) ;end)();local v118=(function() return;end)();while true do if (v117==0) then v118=(function() return 1206 -(696 + 510) ;end)();while true do if (v118==(1 -0)) then v91=(function() return  #"\\";end)();break;end if (v118~=0) then else v92=(function() return v94();end)();v93=(function() return nil;end)();v118=(function() return 1;end)();end end break;end end end end return v91,v92,v93,v94,v95,v96,v97,v98;end;end)();local v52=(function() return function(v99,v100,v101) local v102=(function() return 0;end)();local v103=(function() return;end)();while true do if (v102~=(1262 -(1091 + 171))) then else v103=(function() return 0;end)();while true do if ((0 + 0)==v103) then local v124=(function() return 0 -0 ;end)();while true do if (v124==0) then v99[v100-#"!" ]=(function() return v101();end)();return v99,v100,v101;end end end end break;end end end;end)();local v53=(function() return {};end)();local v54=(function() return {};end)();local v55=(function() return {};end)();local v56=(function() return {v53,v54,nil,v55};end)();local v57=(function() return v23();end)();local v58=(function() return {};end)();for v68= #"~",v57 do FlatIdent_2661B,Type,Cons,v21,v24,v25,v58,v68=(function() return v51(FlatIdent_2661B,Type,Cons,v21,v24,v25,v58,v68);end)();end v56[ #"gha"]=(function() return v21();end)();for v69= #"~",v23() do local v70=(function() return v21();end)();if (v20(v70, #"!", #">")~=0) then else local v106=(function() return 0;end)();local v107=(function() return;end)();local v108=(function() return;end)();local v109=(function() return;end)();while true do if (v106~=(376 -(123 + 251))) then else if (v20(v108, #"\\", #"{")~= #"]") then else v109[2]=(function() return v58[v109[2]];end)();end if (v20(v108,9 -7 ,700 -(208 + 490) )== #",") then v109[ #"xnx"]=(function() return v58[v109[ #"nil"]];end)();end v106=(function() return 3;end)();end if (v106==(1 + 0)) then v109=(function() return {v22(),v22(),nil,nil};end)();if (v107==(836 -(660 + 176))) then local v127=(function() return 0 + 0 ;end)();local v128=(function() return;end)();while true do if (v127==0) then v128=(function() return 202 -(14 + 188) ;end)();while true do if (v128~=0) then else v109[ #"19("]=(function() return v22();end)();v109[ #"?id="]=(function() return v22();end)();break;end end break;end end elseif (v107== #">") then v109[ #"-19"]=(function() return v23();end)();elseif (v107==2) then v109[ #"19("]=(function() return v23() -((677 -(534 + 141))^16) ;end)();elseif (v107== #"19(") then local v136=(function() return 0 + 0 ;end)();local v137=(function() return;end)();while true do if (0~=v136) then else v137=(function() return 0 + 0 ;end)();while true do if ((0 + 0)==v137) then v109[ #"-19"]=(function() return v23() -((3 -1)^(25 -9)) ;end)();v109[ #"?id="]=(function() return v22();end)();break;end end break;end end end v106=(function() return 5 -3 ;end)();end if (v106==0) then local v121=(function() return 0 + 0 ;end)();local v122=(function() return;end)();while true do if (v121==(0 + 0)) then v122=(function() return 0;end)();while true do if (v122~=1) then else v106=(function() return 1;end)();break;end if (v122==0) then local v133=(function() return 396 -(115 + 281) ;end)();while true do if (v133==(2 -1)) then v122=(function() return 1 + 0 ;end)();break;end if (v133==(0 -0)) then v107=(function() return v20(v70,7 -5 , #"-19");end)();v108=(function() return v20(v70, #".dev",873 -(550 + 317) );end)();v133=(function() return 1 -0 ;end)();end end end end break;end end end if (v106==(3 -0)) then if (v20(v108, #"19(", #"xxx")== #"!") then v109[ #"0313"]=(function() return v58[v109[ #"0313"]];end)();end v53[v69]=(function() return v109;end)();break;end end end end for v71= #":",v23() do v54,v71,v28=(function() return v52(v54,v71,v28);end)();end return v56;end local function v29(v60,v61,v62) local v63=v60[1];local v64=v60[5 -3 ];local v65=v60[288 -((1924 -(1010 + 780)) + 151) ];return function(...) local v72=v63;local v73=v64;local v74=v65;local v75=v27;local v76=1 + 0 ;local v77= -1;local v78={};local v79={...};local v80=v12("#",...) -(1 -0) ;local v81={};local v82={};for v104=1990 -(582 + 1408) ,v80 do if ((v104>=v74) or (2070>=4037)) then v78[v104-v74 ]=v79[v104 + (3 -2) ];else v82[v104]=v79[v104 + (1 -0) ];end end local v83=(v80-v74) + 1 ;local v84;local v85;while true do local v105=0 -0 ;while true do if ((1824 -((3501 -2306) + 629))==v105) then v84=v72[v76];v85=v84[1 -0 ];v105=1;end if ((2705==2705) and (v105==(242 -(187 + (1890 -(1045 + 791)))))) then if ((61==61) and (v85<=(799 -(162 + 618)))) then if (v85<=(7 + 2)) then if (v85<=(3 + 1)) then if (((568<=911) and (v85<=(1 -0))) or (699>=1296)) then if ((v85==0) or (1783>=3616)) then do return;end else local v138=v82[v84[4]];if ((3285<4228) and  not v138) then v76=v76 + ((2 -1) -0) ;else local v240=0 + 0 ;while true do if (v240==(1636 -(1373 + 263))) then v82[v84[1002 -(451 + 549) ]]=v138;v76=v84[3];break;end end end end elseif (v85<=(1 + 1)) then local v139=0 -0 ;local v140;while true do if (((3916>3328) and ((0 -0)==v139)) or (3913>4527)) then v140=v84[1386 -(746 + 638) ];v82[v140](v82[v140 + 1 + 0 ]);break;end end elseif (v85>3) then local v241=v84[2 -0 ];local v242=v84[4];local v243=v241 + (343 -(218 + 123)) ;local v244={v82[v241](v82[v241 + 1 + 0 ],v82[v243])};for v327=1 + 0 ,v242 do v82[v243 + v327 ]=v244[v327];end local v245=v244[1];if v245 then v82[v243]=v245;v76=v84[563 -(306 + (387 -133)) ];else v76=v76 + 1 + 0 ;end else local v246=0 -0 ;local v247;local v248;while true do if (v246==(1467 -(899 + 568))) then v247=v84[2];v248={};v246=1 + 0 ;end if (v246==(2 -1)) then for v380=604 -(268 + 335) , #v81 do local v381=v81[v380];for v384=290 -(60 + 230) , #v381 do local v385=v381[v384];local v386=v385[573 -(426 + (651 -(351 + 154))) ];local v387=v385[1 + 1 ];if ((4376>817) and (2500<3839) and (v386==v82) and (v387>=v247)) then local v393=0;while true do if ((4861>824) and (v393==(1456 -(282 + 1174)))) then v248[v387]=v386[v387];v385[812 -(569 + (1816 -(1281 + 293))) ]=v248;break;end end end end end break;end end end elseif (v85<=(17 -11)) then if (v85==(271 -(28 + 238))) then for v215=v84[1 + 1 ],v84[3] do v82[v215]=nil;end else local v141=v73[v84[1027 -(706 + 318) ]];local v142;local v143={};v142=v10({},{__index=function(v217,v218) local v219=v143[v218];return v219[1252 -(721 + 530) ][v219[1273 -(945 + 326) ]];end,__newindex=function(v220,v221,v222) local v223=v143[v221];v223[2 -1 ][v223[2 + 0 ]]=v222;end});for v225=(1566 -865) -(271 + 429) ,v84[4 + (1559 -(1381 + 178)) ] do local v226=0;local v227;while true do if (v226==(1500 -(1408 + 92))) then v76=v76 + 1 ;v227=v72[v76];v226=1087 -(461 + 625) ;end if (((507==507) and (v226==(1289 -(993 + 295)))) or (1383>=2131)) then if ((v227[1 + 0 + 0 ]==(1210 -(418 + 753))) or (1876>=2541)) then v143[v225-1 ]={v82,v227[1 + 2 ]};else v143[v225-(1 + 0) ]={v61,v227[3]};end v81[ #v81 + (1770 -(1749 + 20)) ]=v143;break;end end end v82[v84[2]]=v29(v141,v142,v62);end elseif ((240<=3165) and (v85<=7)) then local v145;local v146;local v145,v147;local v148;local v149;v82[v84[1 + 1 ]]=v62[v84[1325 -(1249 + 73) ]];v76=v76 + 1 + 0 ;v84=v72[v76];v82[v84[1147 -(466 + 679) ]]=v61[v84[3]];v76=v76 + 1 ;v84=v72[v76];v149=v84[4 -(472 -(381 + 89)) ];v148=v82[v84[8 -5 ]];v82[v149 + (1901 -(106 + 1794)) ]=v148;v82[v149]=v148[v84[2 + 2 ]];v76=v76 + 1 + 0 + 0 ;v84=v72[v76];v149=v84[5 -3 ];v145,v147=v75(v82[v149](v82[v149 + (2 -1) ]));v77=(v147 + v149) -(115 -(3 + 1 + 110)) ;v146=584 -(57 + 527) ;for v228=v149,v77 do v146=v146 + (1428 -(41 + 1386)) ;v82[v228]=v145[v146];end v76=v76 + (104 -(17 + 86)) ;v84=v72[v76];v149=v84[2 + 0 ];v145={v82[v149](v13(v82,v149 + 1 ,v77))};v146=0 -0 ;for v231=v149,v84[170 -(122 + 44) ] do v146=v146 + 1 ;v82[v231]=v145[v146];end v76=v76 + 1 ;v84=v72[v76];v76=v84[5 -2 ];elseif (v85==((1182 -(1074 + 82)) -18)) then v76=v84[3 + (0 -0) ];else v82[v84[1 + 1 ]]=v82[v84[3]][v84[7 -3 ]];end elseif ((1782<=3772) and (834>=805) and (v85<=(1798 -(214 + 1570)))) then if (v85<=(76 -(30 + 35))) then if ((v85>(7 + 3)) or (3812<2316)) then v82[v84[1259 -(1043 + 214) ]][v84[(1466 -(990 + 465)) -(4 + 4) ]]=v84[1216 -(323 + 889) ];else local v165=0 -(0 + 0) ;local v166;local v167;local v168;local v169;while true do if (v165==(581 -(361 + 219))) then v77=(v168 + v166) -1 ;v169=320 -(53 + 267) ;v165=1 + 1 + 0 ;end if (v165==(0 -0)) then v166=v84[2];v167,v168=v75(v82[v166](v82[v166 + (414 -(15 + 398)) ]));v165=983 -(18 + 964) ;end if (v165==2) then for v339=v166,v77 do local v340=0 -0 ;while true do if ((v340==(0 + 0)) or (2652<=1533)) then v169=v169 + 1 + 0 ;v82[v339]=v167[v169];break;end end end break;end end end elseif (v85<=(862 -(20 + 830))) then local v170=v84[2 + 0 ];local v171=v82[v84[129 -(116 + 10) ]];v82[v170 + 1 + 0 ]=v171;v82[v170]=v171[v84[742 -(542 + 196) ]];elseif ((v85==(27 -(1740 -(1668 + 58)))) or (4700<813)) then local v252=0 + 0 ;local v253;while true do if (v252==(1 + 0)) then v84=v72[v76];v82[v84[(627 -(512 + 114)) + 1 ]]=v61[v84[7 -4 ]];v76=v76 + (2 -1) ;v252=(4048 -2495) -((2327 -1201) + 425) ;end if ((v252==((1416 -1009) -(118 + 287))) or (3598<1460)) then v84=v72[v76];v82[v84[2]]=v82[v84[3]];v76=v76 + (3 -2) ;v252=1124 -(118 + 1003) ;end if (v252==(0 -0)) then v253=nil;v82[v84[2]]=v82[v84[380 -(142 + 235) ]][v84[18 -14 ]];v76=v76 + 1 ;v252=1 + 0 + 0 ;end if ((3199<4050) and ((v252==(980 -(553 + 80 + 344))) or (4116<1192))) then v84=v72[v76];v253=v84[3 -1 ];v82[v253]=v82[v253](v13(v82,v253 + 1 + 0 ,v84[3]));v252=4 + 0 ;end if (v252==4) then v76=v76 + 1 + 0 ;v84=v72[v76];v82[v84[1 + 1 ]]= not v82[v84[2 + 1 ]];break;end end else v82[v84[2]]=v62[v84[6 -3 ]];end elseif (v85<=(44 -28)) then if (v85>(33 -18)) then if v82[v84[1 + 1 ]] then v76=v76 + 1 ;else v76=v84[3];end elseif ( not v82[v84[9 -7 ]] or (4951<4430)) then v76=v76 + (754 -(239 + 514)) ;else v76=v84[2 + 0 + (3 -2) ];end elseif ((v85<=17) or (3377<=903)) then local v175;local v176;local v177;v82[v84[2]]={};v76=v76 + 1 ;v84=v72[v76];v82[v84[(3325 -(109 + 1885)) -(797 + 532) ]]=v84[3 + 0 ];v76=v76 + 1 + 0 ;v84=v72[v76];v82[v84[4 -2 ]]=v84[(2674 -(1269 + 200)) -(373 + 829) ];v76=v76 + (732 -(476 + 255)) ;v84=v72[v76];v82[v84[1132 -(369 + 761) ]]=v84[2 + 1 ];v76=v76 + (1 -0) ;v84=v72[v76];v177=v84[3 -1 ];v176=v82[v177];v175=v84[3];for v234=1,v175 do v176[v234]=v82[v177 + v234 ];end elseif (v85==(256 -(64 + 174))) then local v258=v84[(1 -0) + 1 ];local v259=v82[v258];local v260=v84[(818 -(98 + 717)) -0 ];for v331=337 -(144 + 192) ,v260 do v259[v331]=v82[v258 + v331 ];end elseif ((96==96) and (3976>=439) and (v84[218 -(42 + 174) ]==v82[v84[(830 -(802 + 24)) + 0 ]])) then v76=v76 + 1 ;else v76=v84[3 + 0 ];end elseif (v85<=29) then if (v85<=24) then if ((v85<=21) or (2739>4008)) then if (v85==(9 + 11)) then v82[v84[2]]=v61[v84[3]];else v82[v84[2]]=v84[1507 -(363 + (1967 -826)) ];end elseif (v85<=(27 -5)) then local v193=v84[1582 -(175 + 1008 + 306 + 91) ];local v194={v82[v193](v13(v82,v193 + 1 + 0 ,v77))};local v195=(0 -0) + (0 -0) ;for v237=v193,v84[1979 -(1913 + 62) ] do local v238=0 + 0 ;while true do if ((3752==3752) and (v238==(0 -0))) then v195=v195 + (1934 -(565 + 1368)) ;v82[v237]=v194[v195];break;end end end elseif (((4046>2695) and (v85>((31 + 55) -63))) or (23==1134)) then v82[v84[1663 -(1477 + 184) ]]={};else v82[v84[(1 + 1) -0 ]]= not v82[v84[3 + 0 + 0 + 0 ]];end elseif ((v85<=(882 -(564 + 137 + 155))) or (3545==3197)) then if ((v85>(42 -17)) or (2693>=4111)) then local v196=v84[5 -(1436 -(797 + 636)) ];v82[v196](v13(v82,v196 + (305 -(244 + 60)) ,v84[3 + (0 -0) ]));else local v197=0;local v198;while true do if (v197==((2095 -(1427 + 192)) -(41 + 435))) then v198=v84[1003 -(938 + 63) ];do return v13(v82,v198,v198 + v84[3 + 0 ] );end break;end end end elseif ((v85<=(1152 -(325 + 611 + 189))) or (4316<=2146)) then local v199=v84[1 + 1 ];v82[v199]=v82[v199](v13(v82,v199 + (1614 -(1565 + 48)) ,v84[3]));elseif (v85>28) then local v263=0;local v264;while true do if (v263==(3 + 1)) then v84=v72[v76];v264=v84[2];v82[v264]=v82[v264](v13(v82,v264 + (1139 -((1815 -1033) + 356)) ,v84[270 -(159 + 17 + 91) ]));v263=13 -8 ;end if (v263==(1 -0)) then v84=v72[v76];v82[v84[1094 -(975 + 117) ]]=v82[v84[1878 -(157 + 1718) ]][v84[4]];v76=v76 + 1 + 0 + 0 ;v263=6 -4 ;end if (v263==(10 -7)) then v84=v72[v76];v82[v84[2]]=v82[v84[3]];v76=v76 + (1019 -((1023 -(192 + 134)) + 321)) ;v263=10 -6 ;end if ((2394>373) and (v263==(3 -1))) then v84=v72[v76];v82[v84[4 -2 ]]=v61[v84[2 + 1 ]];v76=v76 + (1 -(1276 -(316 + 960))) ;v263=7 -4 ;end if (5==v263) then v76=v76 + ((684 + 544) -(322 + 905)) ;v84=v72[v76];if  not v82[v84[613 -(602 + 9) ]] then v76=v76 + ((919 + 271) -(449 + 740)) ;else v76=v84[875 -(826 + 46) ];end break;end if ((4155<=4232) and (v263==(947 -(245 + 702)))) then v264=nil;v82[v84[6 -4 ]]=v62[v84[1 + 2 ]];v76=v76 + (1899 -(260 + 1638)) ;v263=1;end end elseif (v82[v84[442 -(382 + 58) ]]==v84[12 -8 ]) then v76=v76 + 1 + 0 ;else v76=v84[5 -2 ];end elseif ((v85<=(100 -66)) or (3546<=2809)) then if ((4904>2166) and (v85<=(1236 -(902 + 303)))) then if (v85>(65 -35)) then v82[v84[4 -2 ]]();else local v201=v84[1 + 1 ];v82[v201]=v82[v201](v82[v201 + (1691 -(1121 + 569)) ]);end elseif (v85<=(246 -(22 + 192))) then v82[v84[2]][v84[686 -(483 + 200) ]]=v82[v84[1467 -(1404 + 59) ]];elseif ((109>=90) and ((v85==(90 -57)) or (3581==3473))) then do return v82[v84[2 -0 ]];end else local v265;local v266;v82[v84[767 -(468 + 297) ]]=v82[v84[565 -(334 + 228) ]][v84[4]];v76=v76 + (3 -2) ;v84=v72[v76];v82[v84[2]]=v82[v84[6 -(3 + 0) ]][v84[6 -2 ]];v76=v76 + 1 + 0 ;v84=v72[v76];v266=v84[2];v265=v82[v84[239 -(141 + 95) ]];v82[v266 + 1 + (0 -0) ]=v265;v82[v266]=v265[v84[4]];v76=v76 + (2 -1) ;v84=v72[v76];v82[v84[2]]=v84[6 -3 ];v76=v76 + 1 + 0 ;v84=v72[v76];v266=v84[(556 -(83 + 468)) -3 ];v82[v266]=v82[v266](v13(v82,v266 + 1 + 0 ,v84[2 + 1 ]));v76=v76 + ((1807 -(1202 + 604)) -0) ;v84=v72[v76];if ((4978>2905) and v82[v84[2 + 0 ]]) then v76=v76 + ((765 -601) -(92 + 71)) ;else v76=v84[2 + 1 ];end end elseif (v85<=((101 -40) -24)) then if ((v85<=(800 -(574 + 191))) or (3026<=2280)) then local v205;v82[v84[2]]=v84[3 + 0 ];v76=v76 + (2 -1) ;v84=v72[v76];v205=v84[2 + 0 ];v82[v205](v13(v82,v205 + (850 -(254 + 595)) ,v84[129 -(55 + 71) ]));v76=v76 + (1 -0) ;v84=v72[v76];v82[v84[1792 -((1586 -1013) + 1217) ]]=v61[v84[8 -5 ]];v76=v76 + 1 + 0 ;v84=v72[v76];v82[v84[2 -(325 -(45 + 280)) ]]();v76=v76 + (940 -(714 + 225)) ;v84=v72[v76];v76=v84[3];elseif ((4995>3348) and (v85==(104 -68))) then local v279;local v280;v280=v84[2 -0 ];v279=v82[v84[1 + 2 ]];v82[v280 + (1 -0) ]=v279;v82[v280]=v279[v84[4]];v76=v76 + (807 -(118 + 688)) ;v84=v72[v76];v82[v84[50 -(25 + 0 + 23) ]]=v84[1 + 2 ];v76=v76 + (1887 -(927 + 959)) ;v84=v72[v76];v280=v84[2];v82[v280]=v82[v280](v13(v82,v280 + (3 -2) ,v84[3]));v76=v76 + (733 -(16 + 716)) ;v84=v72[v76];v82[v84[3 -1 ]]=v82[v84[3]];v76=v76 + 1 ;v84=v72[v76];v82[v84[99 -(11 + 86) ]]=v62[v84[(6 + 0) -3 ]];v76=v76 + (286 -(175 + 110)) ;v84=v72[v76];v280=v84[2];v279=v82[v84[6 -3 ]];v82[v280 + (4 -3) ]=v279;v82[v280]=v279[v84[4]];v76=v76 + (1797 -(503 + 1293)) ;v84=v72[v76];v82[v84[5 -3 ]]=v84[3];v76=v76 + 1 + 0 ;v84=v72[v76];v280=v84[1063 -(810 + 251) ];v82[v280]=v82[v280](v13(v82,v280 + 1 + 0 ,v84[1 + 2 ]));v76=v76 + 1 ;v84=v72[v76];v82[v84[2]]=v82[v84[3 + 0 ]];v76=v76 + (534 -(43 + 490)) ;v84=v72[v76];v82[v84[2]]=v82[v84[736 -(711 + 22) ]][v84[15 -11 ]];else local v302=0;local v303;while true do if ((v302==(859 -(88 + 152 + 619))) or (754>3724) or (1653<=1108)) then v303=v82[v84[1 + 3 ]];if v303 then v76=v76 + (1 -0) ;else v82[v84[1 + 1 + 0 ]]=v303;v76=v84[1747 -(1344 + 400) ];end break;end end end elseif (v85<=(443 -(45 + 210 + 150))) then local v213=v84[2];local v214=v82[v213];for v239=v213 + 1 + 0 ,v84[2 + 1 ] do v7(v214,v82[v239]);end elseif ((217>=57) and (v85>39)) then local v304;local v305;v305=v84[8 -6 ];v304=v82[v84[(16 -7) -6 ]];v82[v305 + (1740 -(404 + 1335)) ]=v304;v82[v305]=v304[v84[410 -(183 + 223) ]];v76=v76 + (1 -0) ;v84=v72[v76];v82[v84[(1913 -(340 + 1571)) + 0 ]]=v84[2 + 1 ];v76=v76 + (338 -(10 + 327)) ;v84=v72[v76];v305=v84[2 + 0 ];v82[v305]=v82[v305](v13(v82,v305 + (339 -(118 + 87 + 133)) ,v84[1 + 2 ]));v76=v76 + (450 -(108 + 341)) ;v84=v72[v76];v82[v84[1 + 1 ]]=v82[v84[12 -9 ]];v76=v76 + (1494 -(711 + (2554 -(1733 + 39)))) ;v84=v72[v76];v82[v84[3 -1 ]]={};v76=v76 + 1 ;v84=v72[v76];v82[v84[471 -(270 + 199) ]]=v84[3];v76=v76 + 1 + 0 ;v84=v72[v76];v82[v84[1821 -(580 + 1239) ]]=v84[3];v76=v76 + (2 -1) ;v84=v72[v76];v82[v84[2 + 0 ]]=v84[1 + 2 ];v76=v76 + (2 -1) ;v84=v72[v76];v82[v84[2]]=v84[3];v76=v76 + 1 + (1034 -(125 + 909)) ;v84=v72[v76];v82[v84[2]]=v84[3];else v82[v84[(1952 -(1096 + 852)) -2 ]]=v82[v84[2 + 1 ]];end v76=v76 + (1168 -(645 + 522)) ;break;end end end end;end return v29(v28(),{},v17)(...);end return v15("LOL!193Q00028Q00026Q00F03F03093Q00776F726B7370616365030C3Q0057616974466F724368696C6403073Q005479632Q6F6E7303083Q00496E73616E69747903053Q004769616E7403043Q004461726B03053Q005370696B652Q033Q0057656203063Q005374726F6E6703053Q0053746F6E6503053Q004D6167696303053Q0053746F726D027Q0040026Q00084003043Q0067616D65030A3Q004765745365727669636503073Q00506C6179657273030A3Q0052756E53657276696365030B3Q004C6F63616C506C61796572026Q001040030E3Q00436861726163746572412Q64656403073Q00436F2Q6E656374030D3Q0052656E6465725374652Q70656400493Q0012153Q00014Q0005000100093Q00261C3Q0019000100020004083Q0019000100120E000A00033Q002028000A000A000400122Q000C00056Q000A000C00024Q0004000A6Q000A00063Q00122Q000B00063Q00122Q000C00073Q00122Q000D00083Q00122Q000E00093Q00122Q000F000A3Q0012150010000B4Q0012000A000600012Q00270005000A4Q0011000A00033Q00122Q000B000C3Q00122Q000C000D3Q00122Q000D000E6Q000A000300012Q00270006000A3Q0012153Q000F3Q00261C3Q00210001000F0004083Q002100012Q0005000700073Q002Q0600073Q000100022Q00273Q00064Q00273Q00054Q0005000800083Q0012153Q00103Q00261C3Q002F000100010004083Q002F000100120E000A00113Q002024000A000A001200122Q000C00136Q000A000C00024Q0001000A3Q00122Q000A00113Q00202Q000A000A001200122Q000C00146Q000A000C00024Q0002000A3Q00202Q0003000100150012153Q00023Q00261C3Q003C000100160004083Q003C0001002009000A0003001700200C000A000A0018002Q06000C0001000100012Q00273Q00094Q001A000A000C0001002009000A0002001900200C000A000A0018002Q06000C0002000100012Q00273Q00094Q001A000A000C00010004083Q0047000100261C3Q0002000100100004083Q00020001002Q0600080003000100012Q00273Q00034Q0005000900093Q002Q0600090004000100032Q00273Q00044Q00273Q00074Q00273Q00083Q0012153Q00163Q0004083Q000200012Q00039Q003Q00013Q00053Q00023Q0003053Q007461626C6503043Q0066696E64010F3Q00121D000100013Q00202Q0001000100024Q00028Q00038Q00010003000200062Q0001000D000100010004083Q000D000100120E000100013Q00200D0001000100024Q000200016Q00038Q0001000300024Q000100014Q0021000100028Q00017Q00033Q00028Q00030C3Q0057616974466F724368696C6403103Q0048756D616E6F6964522Q6F7450617274010B3Q001215000100013Q00261C00010001000100010004083Q0001000100200C00023Q0002001223000400036Q0002000400014Q00028Q00020001000100044Q000A00010004083Q000100016Q00019Q003Q00034Q00148Q001F3Q000100016Q00017Q000E3Q00028Q00026Q00F03F030E3Q0046696E6446697273744368696C6403053Q00546F72736F030A3Q00552Q706572546F72736F2Q033Q0049734103083Q00426173655061727403063Q00434672616D65030C3Q005472616E73706172656E6379030A3Q0043616E436F2Q6C696465010003083Q00416E63686F7265642Q0103093Q0043686172616374657201463Q001215000100014Q0005000200043Q00261C00010007000100010004083Q00070001001215000200014Q0005000300033Q001215000100023Q00261C00010002000100020004083Q000200012Q0005000400043Q00261C00020032000100020004083Q0032000100200C000500030003001215000700044Q001B00050007000200060100040015000100050004083Q0015000100200C000500030003001215000700054Q001B0005000700022Q0027000400053Q0006100004004500013Q0004083Q0045000100200C00053Q0006001215000700074Q001B0005000700020006100005004500013Q0004083Q00450001001215000500013Q00261C0005002B000100010004083Q002B0001001215000600013Q00261C00060026000100010004083Q002600010020090007000400080010203Q0008000700300B3Q00090002001215000600023Q00261C00060020000100020004083Q00200001001215000500023Q0004083Q002B00010004083Q0020000100261C0005001D000100020004083Q001D000100300B3Q000A000B00300B3Q000C000D0004083Q004500010004083Q001D00010004083Q0045000100261C0002000A000100010004083Q000A0001001215000500013Q00261C00050039000100020004083Q00390001001215000200023Q0004083Q000A0001000E1300010035000100050004083Q003500012Q001400065Q00200900030006000E00060F00030040000100010004083Q004000016Q00013Q001215000500023Q0004083Q003500010004083Q000A00010004083Q004500010004083Q000200016Q00017Q00093Q0003063Q00697061697273030E3Q0047657444657363656E64616E74732Q033Q0049734103103Q00546F7563685472616E736D692Q74657203063Q00506172656E7403043Q004E616D6503043Q0066696E64030A3Q0047656172476976657231029Q002F3Q0012073Q00016Q00015Q00202Q0001000100024Q000100029Q00000200044Q002C000100200C000500040003001215000700044Q001B0005000700020006100005002C00013Q0004083Q002C000100200900050004000500202200050005000500202Q00050005000600202Q00050005000700122Q000700086Q00050007000200062Q0005002C00013Q0004083Q002C0001001215000500094Q0005000600063Q00261C00050015000100090004083Q0015000100200900070004000500200900070007000500200900070007000500062500060020000100070004083Q002000010020090007000400050020090007000700050020090007000700050020090006000700060006100006002C00013Q0004083Q002C00012Q0014000700014Q0027000800064Q001E0007000200020006100007002C00013Q0004083Q002C00012Q0014000700023Q0020090008000400052Q00020007000200010004083Q002C00010004083Q001500010006043Q0006000100020004083Q000600016Q00017Q00",v9(),...);
