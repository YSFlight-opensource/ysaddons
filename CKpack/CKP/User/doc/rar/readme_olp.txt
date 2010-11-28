○YSFSシーナリー　[Operation Long Pat]

1.インストール方法
ground/ground.lstに以下の行を追加。

User/rar/olp/base.dat User/rar/olp/base_visual.srf User/rar/olp/base_coll.srf
User/rar/olp/lha.dat User/rar/olp/lha_visual.srf User/rar/olp/lha_coll.srf
User/rar/olp/cg21.dat User/rar/olp/cg21.srf User/rar/olp/cg21.srf
User/rar/olp/basesam.dat User/rar/olp/basesam.dnm User/rar/olp/basesam.srf
User/rar/olp/thaad.dat User/rar/olp/thaad.srf User/rar/olp/thaad.srf
User/rar/olp/tochka.dat User/rar/olp/tochka2.srf User/rar/olp/tochka2.srf
User/rar/olp/tochka2.dat User/rar/olp/tochka1.srf User/rar/olp/tochka1.srf
User/rar/olp/m107.dat User/rar/olp/m107.srf User/rar/olp/m107.srf
User/rar/olp/m901.dat User/rar/olp/m901.srf User/rar/olp/m901.srf
User/rar/olp/t-80.dat User/rar/olp/t-80.srf User/rar/olp/t-80c.srf
User/rar/olp/lcac.dat User/rar/olp/lcac.srf User/rar/olp/lcaccoll.srf
User/rar/olp/helico.dat User/rar/olp/helico.srf User/rar/olp/helico_coll.srf
User/rar/olp/rar_hag2.dat User/rar/olp/rar_hag2.srf User/rar/olp/rar_hag2.srf
User/rar/olp/subm.dat User/rar/olp/subm.srf User/rar/olp/subm_coll.srf

及びscenary/scenary.lstに以下の行を追加。

Operation_Long_Pat User/rar/olp/olp.fld User/rar/olp/olp.stp User/rar/olp/olp.yfs
Operation_Long_Pat[lite] User/rar/olp/olp.fld User/rar/olp/olp.stp User/rar/olp/olp_lite.yfs
Operation_Long_Pat[noncombat] User/rar/olp/olp2.fld User/rar/olp/olp.stp User/rar/olp/olp_2.yfs

2.マップについて

とある諸島のとあるビーチで上陸作戦が行われています。
空母・揚陸艦もしくは付近の（隠蔽された）基地から
発進してビーチのトーチカや敵基地を攻撃するのが目的です。
また、揚陸艦より上陸をする事も可能です。
しかしながら航空支援が無いとトーチカやヘリなどにコテンパンにされると思われます。

マップ名のの由来は、AC04のOperation Banker Shotですｗ

◆スタート地点
 BASEAIR_01～03 ： 味方基地の上空です。敵の島に向かいます。
 BASE_01,02     ： 味方基地の中です。カタパルトで発進します。
 BASE_03        ： 味方基地のヘリポートです。STOL性能のある航空機のみ離着陸できます。
 ON_lha1_01,02　： 揚陸艦の甲板上です。
 IN_lha1_01,02　： 揚陸艦のドック内です。
 ON_lha2_01,02　： もう一隻の揚陸艦の甲板上。
 IN_lha2_01,02　：      〃         のドック内。
 HIDEOUT_01     ： 隠れ家のような小さい基地。滑走距離が短め且つ大きさが戦闘機クラス以下の航空機専用。
 ON_CARRIER_01～03：空母上。
 CVN_AIR_01～03 ： 空母上空。
 BEACH_01～03   ： ビーチ上陸地点。02,03にステルス性の無い機体で出現すると数秒後にミサイルが飛んできます。
 ENEMYBASE_01～03,opposite_01～02：敵航空基地滑走路上。noncombat版では01～03は位置が若干違います。
 APPROACH_TO_BASE： 味方基地へのアプローチ。
 APPROACH_TO_ENEMYBASE：航空基地へのアプローチ。noncombat版のみ。
 LIKE_A_SRBM　　： オマケ。島の200000ft上空から真下にマッハ3でスタートします。まさに短距離弾道ミサイル,という感じです。
 
 
◆ミッションについて
・ Operation_Long_Pat (Liteも含む)
こちらは、上で説明した通り上陸作戦を行うマップです。
島全体にIFF2のオブジェクトが散りばめられています。
ビーチ付近にはトーチカや戦車・軽戦車や対戦車ヘリ・短射程SAM・AAA、
島中央のミサイル発射場ではSAMや榴弾砲・長射程SAMがあります。
長射程SAMは高高度の航空機を目標としています。
味方では、ビーチ付近に数台の戦車と2隻の揚陸艦、その南方に空母と巡洋艦(CG-21型)が配置されています。

・　Operation_Long_Pat[noncombat]
上陸作戦が終わった直後という設定です。ビーチのトーチカや対空兵器は一掃されています。
敵航空基地のハンガーなどが残されており、IFF1になっています。
ただ、滑走路やタキシングロードなどに爆弾による大穴が空いていますのでそこは通れません。
オマケとして、航空基地の北東に敵潜水艦がいます。潜水艦は短射程のSAMを備えています。


◇兵器について
・対戦車ヘリ：道を侵攻中の目下の敵にミサイルや機銃を撃ってきます。
・軽戦車：地上において近くに寄ってくるとミサイルを撃ってきます。
・巡洋艦：長射程SAMを備えています。
・長射程SAM：上空100000mまでの射程を備えています。射角は60度～90度です。


◆着陸可能エリアについて

共通：
・ビーチとその近辺の海。ビーチのどこからでも揚陸艦に向かって直進出来るようになっています。
・空母、揚陸艦甲板及びドック内
・敵航空基地
・ビーチから直接航空基地に伸びている2本の道。ミサイル発射場も含む。
　別れ道で警戒標識が立てられている方向は入れません。
・2つの味方基地。HIDEOUTは着陸可能エリアの端っこの角にはオレンジのブイが浮いています。

[noncombat]版のみ：
・島全部の道。港も含む。


3.このマップを使用するに当たっては、当方は責任を負いません。
　各自の責任において使用してください。
　また、YSFSの作者であるCaptainYSさんにこのマップについて苦情や質問をするのも
　止めて下さい。

----------------------------------------------------------------------------------

4.オマケ
揚陸艦のドックから戦車などを載せて発進する為のホバークラフト、
LCACをオマケとして同梱します。

・インストール方法
aircraft/aircraft.lstに以下の行を追加。

User/rar/aircraft/lcac.dat User/rar/aircraft/lcac.dnm User/rar/aircraft/lcaccoll.srf User/rar/aircraft/lcaccockpit.srf

何も無いのも寂しいので機銃とロケットを装備させました。

