2021-03-10T14:44:06+01:00
Scanning C:\xampp\htdocs\wp-content\themes\politybooks
Including file extensions: php
Processed 16180 lines contained in 55 files.
Processing took 5.5123460292816 seconds.

# nuance
#### C:\xampp\htdocs\wp-content\themes\politybooks\check.php
* arrayValueByReference
 * Line 23: `as$Gd=>$W){unset($If[$x][$Gd]);if(is_array($W)){$If[$x][stripslashes($Gd)]=$W;$If[]=&$If[$x][stripslashes($Gd)];}else$If[$x][stripslashes($Gd)]=($Jc?$W:stripslashes($W));}}}}function`
* funcGetArg
 * Line 161: `lang($t,$Ee=null){if(is_string($t)){$xf=array_search($t,get_translations("en"));if($xf!==false)$t=$xf;}global$ca,$vh;$uh=($vh[$t]?$vh[$t]:$t);if(is_array($uh)){$xf=($Ee==1?0:($ca=='cs'||$ca=='sk'?($Ee&&$Ee<5?1:2):($ca=='fr'?(!$Ee?0:1):($ca=='pl'?($Ee%10>1&&$Ee%10<5&&$Ee/10%10!=1?1:2):($ca=='sl'?($Ee%100==1?0:($Ee%100==2?1:($Ee%100==3||$Ee%100==4?2:3))):($ca=='lt'?($Ee%10==1&&$Ee%100!=11?0:($Ee%10>1&&$Ee/10%10!=1?1:2)):($ca=='ru'||$ca=='sr'||$ca=='uk'?($Ee%10==1&&$Ee%100!=11?0:($Ee%10>1&&$Ee%10<5&&$Ee/10%10!=1?1:2)):1)))))));$uh=$uh[$xf];}$Ea=func_get_args();array_shift($Ea);$Pc=str_replace("%d","%s",$uh);if($Pc!=$uh)$Ea[0]=format_number($Ee);return`


# critical
#### C:\xampp\htdocs\wp-content\themes\politybooks\check.php
* deprecatedFunctions
 * Line 159: `';}global$b,$h,$Xb,$fc,$pc,$n,$Uc,$Zc,$ba,$ud,$w,$ca,$Pd,$Ne,$uf,$Lg,$dd,$T,$vh,$Bh,$Ih,$ia;if(!$_SERVER["REQUEST_URI"])$_SERVER["REQUEST_URI"]=$_SERVER["ORIG_PATH_INFO"];if(!strpos($_SERVER["REQUEST_URI"],'?')&&$_SERVER["QUERY_STRING"]!="")$_SERVER["REQUEST_URI"].="?$_SERVER[QUERY_STRING]";$ba=$_SERVER["HTTPS"]&&strcasecmp($_SERVER["HTTPS"],"off");@ini_set("session.use_trans_sid",false);session_cache_limiter("");if(!defined("SID")){session_name("adminer_sid");$F=array(0,preg_replace('~\\?.*~','',$_SERVER["REQUEST_URI"]),"",$ba);if(version_compare(PHP_VERSION,'5.2.0')>=0)$F[]=true;call_user_func_array('session_set_cookie_params',$F);session_start();}remove_slashes(array(&$_GET,&$_POST,&$_COOKIE),$Jc);if(get_magic_quotes_runtime())set_magic_quotes_runtime(false);@set_time_limit(0);@ini_set("zend.ze1_compatibility_mode",false);@ini_set("precision",20);$Pd=array('en'=>'English','ar'=>'العربية','bn'=>'বাংলা','ca'=>'Català','cs'=>'Čeština','da'=>'Dansk','de'=>'Deutsch','es'=>'Español','et'=>'Eesti','fa'=>'فارسی','fr'=>'Français','hu'=>'Magyar','id'=>'Bahasa Indonesia','it'=>'Italiano','ja'=>'日本語','ko'=>'한국어','lt'=>'Lietuvių','nl'=>'Nederlands','no'=>'Norsk','pl'=>'Polski','pt'=>'Português','pt-br'=>'Português (Brazil)','ro'=>'Limba Română','ru'=>'Русский язык','sk'=>'Slovenčina','sl'=>'Slovenski','sr'=>'Српски','ta'=>'த‌மிழ்','th'=>'ภาษาไทย','tr'=>'Türkçe','uk'=>'Українська','vi'=>'Tiếng Việt','zh'=>'简体中文','zh-tw'=>'繁體中文',);function`
 * Line 1180: `connect($N,$V,$G){$this->_link=@mysql_connect(($N!=""?$N:ini_get("mysql.default_host")),("$N$V"!=""?$V:ini_get("mysql.default_user")),("$N$V$G"!=""?$G:ini_get("mysql.default_password")),true,131072);if($this->_link)$this->server_info=mysql_get_server_info($this->_link);else$this->error=mysql_error();return(bool)$this->_link;}function`
 * Line 1181: `set_charset($ab){if(function_exists('mysql_set_charset')){if(mysql_set_charset($ab,$this->_link))return`
 * Line 1182: `true;mysql_set_charset('utf8',$this->_link);}return$this->query("SET NAMES $ab");}function`
 * Line 1183: `quote($P){return"'".mysql_real_escape_string($P,$this->_link)."'";}function`
 * Line 1185: `mysql_select_db($Gb,$this->_link);}function`
 * Line 1186: `query($H,$Ch=false){$I=@($Ch?mysql_unbuffered_query($H,$this->_link):mysql_query($H,$this->_link));$this->error="";if(!$I){$this->errno=mysql_errno($this->_link);$this->error=mysql_error($this->_link);return`
 * Line 1187: `false;}if($I===true){$this->affected_rows=mysql_affected_rows($this->_link);$this->info=mysql_info($this->_link);return`
 * Line 1197: `mysql_result($I->_result,0,$o);}}class`
 * Line 1199: `Min_Result($I){$this->_result=$I;$this->num_rows=mysql_num_rows($I);}function`
 * Line 1201: `mysql_fetch_assoc($this->_result);}function`
 * Line 1203: `mysql_fetch_row($this->_result);}function`
 * Line 1204: `fetch_field(){$J=mysql_fetch_field($this->_result,$this->_offset++);$J->orgtable=$J->table;$J->orgname=$J->name;$J->charsetnr=($J->blob?63:0);return$J;}function`
 * Line 1205: `__destruct(){mysql_free_result($this->_result);}}}elseif(extension_loaded("pdo_mysql")){class`

