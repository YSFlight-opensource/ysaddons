#########################################
YSFS ADDMAP "Orange Bee 2" Created by rar
#########################################
・インストール

User/rar/ob2/target.dat User/rar/ob2/target.srf User/rar/ob2/target_coll.srf
User/rar/ob2/target2.dat User/rar/ob2/target.srf User/rar/ob2/target_coll.srf
User/rar/ob2/target3.dat User/rar/ob2/target.srf User/rar/ob2/target_coll.srf
User/rar/ob2/balloon.dat User/rar/ob2/balloon.srf User/rar/ob2/balloon_coll.srf
User/rar/ob2/iceboat.dat User/rar/ob2/iceboat.srf User/rar/ob2/iceboat.srf
User/rar/ob2/rar_hag_s.dat User/rar/ob2/rar_hag_s.srf User/rar/ob2/rar_hag_s.srf
User/rar/ob2/rar_souko2_s.dat User/rar/ob2/rar_souko2_s.srf User/rar/ob2/rar_souko2_s.srf
User/rar/ob2/subm.dat User/rar/ob2/subm.srf User/rar/ob2/subm.srf
User/rar/ob2/tower_s.dat User/rar/ob2/tower_s.srf User/rar/ob2/tower_s.srf
User/rar/ob2/glob.dat User/rar/ob2/glob.srf User/rar/ob2/glob_coll.srf
User/rar/ob2/potl.dat User/rar/ob2/potl.srf User/rar/ob2/potl_coll.srf
User/rar/ob2/ante.dat User/rar/ob2/ante.srf User/rar/ob2/ante.srf
User/rar/ob2/oiltank2.dat User/rar/ob2/oiltank2.srf User/rar/ob2/oiltank2_coll.srf

ground/ground.lstに上の行を追加

ORANGE_BEE2 User/rar/ob2/ob.fld User/rar/ob2/ob.stp User/rar/ob2/ob.yfs

scenary/scenary.lstに上の行を追加

・マップ主旨
	舞台は南極方面、氷山の浮かぶ海の真中に作られた航空基地周辺にてオレンジ色のターゲットドローン・バルーンを
	追いまわして機銃の腕を磨け(るかも知れません)
	ドローンの種類については 開始位置について を参照のこと。
	また中央基地の西には、巨大な氷山がありそのど真ん中にはどういう建設技術を駆使したのか航空基地もあり
	巨大な気象観測レーダーを備えています。基地からそのレーダーサイトまではトンネルで繋がっており、
	一応トンネル幅より小さい航空機もしくは車なら通ることが出来ます。
	ただし、トンネル内では接地していないと通れないのでご注意下さい。
	
	●着陸可能エリア
		・中央基地の舗装部分・港
		・港の水上（海側との境界線にブイを配置してあります）
		・ペンギンの住む島（イグルーがあるので上空からでも判別できるでしょう）
		・氷山基地の周りの海上 エリア幅約2km
	★オマケ要素
		・ペンギンの住む島
		・青とピンクのペンギンカップル
		・（´・ω・｀) のAA(PC2)
		・領空侵犯の無人偵察機（基地上空を飛んでます)
		・領海侵犯の潜水艦(SAM付き)
・F6,F9視点について
		・F6視点は中央基地ILS * 2 => 氷山基地ILS * 2 => 空母 => グローバルホーク =>
		  ドローン（中速) * 3 => ドローン（高速) * 3 => ドローン (低速) * 3
		  の順番です。
		・F9視点は中央基地管制塔 => 氷山基地管制塔 => 氷山基地レーダーサイト => 潜水艦
		  の順番です。
・開始位置について
	AIRBASE_**_XX
		中央基地滑走路上からスタート **は方角
	AIRBASE_APRON
		基地エプロンからスタート
	ICEBASE_**
		氷山基地滑走路上からスタート **は方角
	ICEBASE_TUNNEL
		氷山の基地からレーダーサイトへのトンネル入り口前からスタート
	ICEBASE_HELOPORT
		氷山基地ヘリポート上からスタート
	AROUND_ICEBASE_XX
		氷山基地周辺の海上よりスタート
	TOWARD_DRONE_XX
		ターゲットドローン（250kt, 高度3000m付近)の正面方向よりスタート
	TOWARD_DRONE_01(high)
		ターゲットドローン（550kt, 高度10000m付近)の正面方向よりスタート
	TOWARD_DRONE_01(low)
		ターゲットドローン（100kt, 高度30m付近)の正面方向よりスタート
	TOWARD_BALLOON_XX
		ターゲットバルーンエリアにてスタート
	ON_CARRIER_XX
		空母上にてスタート
	AIRBASE_AIR_XX
		中央基地上空にてスタート
	ICEBASE_AIR_XX
		氷山基地上空にてスタート

・注意
	MAPをインストールまた利用して事に関して・問い合わせなどは絶対にYSFS作者山川氏になさらないようお願いします。
	上記のメールなどは当方にお願いします。
	enter_the_nation@hotmail.com - rar