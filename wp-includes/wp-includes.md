2021-03-10T18:31:03+01:00
Scanning C:\xampp\htdocs\wp-includes
Including file extensions: php
Processed 265665 lines contained in 516 files.
Processing took 46.710662841797 seconds.

# critical
#### C:\xampp\htdocs\wp-includes\ID3\getid3.php
* deprecatedFunctions
 * Line 261: `			if (get_magic_quotes_runtime()) {`
 * Line 262: `				$this->startup_error .= 'magic_quotes_runtime must be disabled before running getID3(). Surround getid3 block by set_magic_quotes_runtime(0) and set_magic_quotes_runtime(1).'."\n";`

#### C:\xampp\htdocs\wp-includes\IXR\class-IXR-base64.php
* oldClassConstructors
 * Line 21: `	public function IXR_Base64( $data ) {`

#### C:\xampp\htdocs\wp-includes\IXR\class-IXR-client.php
* oldClassConstructors
 * Line 51: `	public function IXR_Client( $server, $path = false, $port = 80, $timeout = 15 ) {`

#### C:\xampp\htdocs\wp-includes\IXR\class-IXR-clientmulticall.php
* oldClassConstructors
 * Line 22: `	public function IXR_ClientMulticall( $server, $path = false, $port = 80 ) {`

#### C:\xampp\htdocs\wp-includes\IXR\class-IXR-date.php
* oldClassConstructors
 * Line 31: `	public function IXR_Date( $time ) {`

#### C:\xampp\htdocs\wp-includes\IXR\class-IXR-error.php
* oldClassConstructors
 * Line 23: `	public function IXR_Error( $code, $message ) {`

#### C:\xampp\htdocs\wp-includes\IXR\class-IXR-introspectionserver.php
* oldClassConstructors
 * Line 51: `	public function IXR_IntrospectionServer() {`

#### C:\xampp\htdocs\wp-includes\IXR\class-IXR-message.php
* oldClassConstructors
 * Line 37: `	public function IXR_Message( $message ) {`

#### C:\xampp\htdocs\wp-includes\IXR\class-IXR-request.php
* oldClassConstructors
 * Line 37: `	public function IXR_Request( $method, $args ) {`

#### C:\xampp\htdocs\wp-includes\IXR\class-IXR-server.php
* oldClassConstructors
 * Line 31: `	public function IXR_Server( $callbacks = false, $data = false, $wait = false ) {`

#### C:\xampp\htdocs\wp-includes\IXR\class-IXR-value.php
* oldClassConstructors
 * Line 36: `	public function IXR_Value( $data, $type = false ) {`

#### C:\xampp\htdocs\wp-includes\Text\Diff\Renderer.php
* oldClassConstructors
 * Line 45: `	public function Text_Diff_Renderer( $params = array() ) {`

#### C:\xampp\htdocs\wp-includes\Text\Diff.php
* oldClassConstructors
 * Line 55: `	public function Text_Diff( $engine, $params ) {`
 * Line 310: `	public function Text_MappedDiff( $from_lines, $to_lines,`
 * Line 359: `	public function Text_Diff_Op_copy( $orig, $final = false ) {`
 * Line 386: `	public function Text_Diff_Op_delete( $lines ) {`
 * Line 413: `	public function Text_Diff_Op_add( $lines ) {`
 * Line 440: `	public function Text_Diff_Op_change( $orig, $final ) {`

#### C:\xampp\htdocs\wp-includes\atomlib.php
* oldClassConstructors
 * Line 93: `	public function AtomParser() {`

#### C:\xampp\htdocs\wp-includes\class-json.php
* oldClassConstructors
 * Line 152: `	public function Services_JSON( $use = 0 ) {`

#### C:\xampp\htdocs\wp-includes\class-phpass.php
* oldClassConstructors
 * Line 54: `	public function PasswordHash( $iteration_count_log2, $portable_hashes ) {`

#### C:\xampp\htdocs\wp-includes\class-phpmailer.php
* deprecatedFunctions
 * Line 2518: `            $magic_quotes = ( PHP_VERSION_ID < 70400 && get_magic_quotes_runtime() ); // WP: Patched for PHP 7.4.`
 * Line 2521: `                    set_magic_quotes_runtime(false);`
 * Line 2533: `                    set_magic_quotes_runtime($magic_quotes);`

#### C:\xampp\htdocs\wp-includes\class-pop3.php
* oldClassConstructors
 * Line 60: `	public function POP3( $server = '', $timeout = '' ) {`

#### C:\xampp\htdocs\wp-includes\class-requests.php
* variableInterpolation
 * Line 169: `			return new self::$transport[$cap_string]();`
 * Line 192: `		return new self::$transport[$cap_string]();`

#### C:\xampp\htdocs\wp-includes\class-wp-widget-factory.php
* oldClassConstructors
 * Line 36: `	public function WP_Widget_Factory() {`

#### C:\xampp\htdocs\wp-includes\class-wp-widget.php
* oldClassConstructors
 * Line 174: `	public function WP_Widget( $id_base, $name, $widget_options = array(), $control_options = array() ) {`

#### C:\xampp\htdocs\wp-includes\pomo\entry.php
* oldClassConstructors
 * Line 64: `		public function Translation_Entry( $args = array() ) {`

#### C:\xampp\htdocs\wp-includes\pomo\streams.php
* oldClassConstructors
 * Line 24: `		public function POMO_Reader() {`
 * Line 138: `		public function POMO_FileReader( $filename ) {`
 * Line 207: `		public function POMO_StringReader( $str = '' ) {`
 * Line 266: `		public function POMO_CachedFileReader( $filename ) {`
 * Line 285: `		function POMO_CachedIntFileReader( $filename ) {`

#### C:\xampp\htdocs\wp-includes\rss.php
* oldClassConstructors
 * Line 85: `	public function MagpieRSS( $source ) {`
 * Line 635: `	public function RSSCache( $base = '', $age = '' ) {`

#### C:\xampp\htdocs\wp-includes\wp-db.php
* deprecatedFunctions
 * Line 719: `					$set_charset_succeeded = mysql_set_charset( $charset, $dbh );`
 * Line 726: `					mysql_query( $query, $dbh );`
 * Line 746: `				$res = mysql_query( 'SELECT @@SESSION.sql_mode', $this->dbh );`
 * Line 758: `				$modes_str = mysql_result( $res, 0 );`
 * Line 783: `			mysql_query( "SET SESSION sql_mode='$modes_str'", $this->dbh );`
 * Line 962: `			$success = mysql_select_db( $db, $dbh );`
 * Line 1017: `	 * Real escape, using mysqli_real_escape_string() or mysql_real_escape_string()`
 * Line 1020: `	 * @see mysql_real_escape_string()`
 * Line 1031: `				$escaped = mysql_real_escape_string( $string, $this->dbh );`
 * Line 1287: `				$str = mysql_error( $this->dbh );`
 * Line 1410: `			mysql_free_result( $this->result );`
 * Line 1481: `				$this->dbh = mysql_connect( $this->dbhost, $this->dbuser, $this->dbpassword, $new_link, $client_flags );`
 * Line 1484: `				$this->dbh = @mysql_connect( $this->dbhost, $this->dbuser, $this->dbpassword, $new_link, $client_flags );`
 * Line 1593: `			if ( ! empty( $this->dbh ) && mysql_ping( $this->dbh ) ) {`
 * Line 1704: `					$mysql_errno = mysql_errno( $this->dbh );`
 * Line 1727: `				$this->last_error = mysql_error( $this->dbh );`
 * Line 1746: `				$this->rows_affected = mysql_affected_rows( $this->dbh );`
 * Line 1753: `					$this->insert_id = mysql_insert_id( $this->dbh );`
 * Line 1766: `				while ( $row = mysql_fetch_object( $this->result ) ) {`
 * Line 1779: `	 * Internal function to perform the mysql_query() call.`
 * Line 1794: `			$this->result = mysql_query( $query, $this->dbh );`
 * Line 2773: `							$connection_charset = mysql_client_encoding();`
 * Line 2960: `			$num_fields = mysql_num_fields( $this->result );`
 * Line 2962: `				$this->col_info[ $i ] = mysql_fetch_field( $this->result, $i );`
 * Line 3034: `					$error = mysql_error( $this->dbh );`
 * Line 3036: `					$error = mysql_error();`
 * Line 3067: `			$closed = mysql_close( $this->dbh );`
 * Line 3157: `					$client_version = mysql_get_client_info();`
 * Line 3198: `			$server_info = mysql_get_server_info( $this->dbh );`


# nuance
#### C:\xampp\htdocs\wp-includes\ID3\module.audio-video.asf.php
* hexadecimalString
 * Line 1051: `						$this->warning('data_object.reserved ('.getid3_lib::PrintHexBytes($thisfile_asf_dataobject['reserved']).') does not match expected value of "0x0101"');`

#### C:\xampp\htdocs\wp-includes\ID3\module.audio-video.riff.php
* hexadecimalString
 * Line 1224: `				throw new Exception('expecting "0x38000000" at offset '.($startoffset +   8).', found "'.getid3_lib::PrintHexBytes(substr($AMVheader,   8, 4)).'"');`

#### C:\xampp\htdocs\wp-includes\IXR\class-IXR-client.php
* funcGetArg
 * Line 56: `        $args = func_get_args();`

#### C:\xampp\htdocs\wp-includes\IXR\class-IXR-clientmulticall.php
* funcGetArg
 * Line 27: `        $args = func_get_args();`

#### C:\xampp\htdocs\wp-includes\Requests\IDNAEncoder.php
* foreachByReference
 * Line 42: `		foreach ($parts as &$part) {`

#### C:\xampp\htdocs\wp-includes\class-requests.php
* foreachByReference
 * Line 395: `		foreach ($requests as $id => &$request) {`
 * Line 435: `		foreach ($responses as $id => &$response) {`

#### C:\xampp\htdocs\wp-includes\class-simplepie.php
* funcGetArg
 * Line 568: `			$args = func_get_args();`

#### C:\xampp\htdocs\wp-includes\class-wp-admin-bar.php
* funcGetArg
 * Line 104: `			$args = array_merge( array( 'parent' => $args ), func_get_arg( 2 ) );`

#### C:\xampp\htdocs\wp-includes\class-wp-http-ixr-client.php
* funcGetArg
 * Line 48: `		$args    = func_get_args();`

#### C:\xampp\htdocs\wp-includes\class-wp-rewrite.php
* funcGetArg
 * Line 1530: `			$args['ep_mask'] = func_get_arg( 3 );`

#### C:\xampp\htdocs\wp-includes\cron.php
* funcGetArg
 * Line 371: `		$args = array_slice( func_get_args(), 1 );`

#### C:\xampp\htdocs\wp-includes\plugin.php
* funcGetArg
 * Line 173: `	$args = func_get_args();`
 * Line 214: `		$all_args            = func_get_args();`
 * Line 415: `		$all_args            = func_get_args();`
 * Line 477: `		$all_args            = func_get_args();`

#### C:\xampp\htdocs\wp-includes\post.php
* arrayValueByReference
 * Line 5489: `			$types[ preg_replace( '/^([^.]*).*$/', '$1', wp_basename( $file ) ) ] =& $icon_files[ $file ];`

#### C:\xampp\htdocs\wp-includes\rewrite.php
* funcGetArg
 * Line 186: `		$args['ep_mask'] = func_get_arg( 3 );`

#### C:\xampp\htdocs\wp-includes\theme.php
* funcGetArg
 * Line 684: `		$stylesheet = func_get_arg( 1 );`

#### C:\xampp\htdocs\wp-includes\user.php
* arrayValueByReference
 * Line 822: `		$result['avail_roles'] =& $role_counts;`
 * Line 852: `		$result['avail_roles'] =& $avail_roles;`

