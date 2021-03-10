2021-03-10T14:20:09+01:00
Scanning C:\xampp\htdocs\wp-content\plugins\updraftplus
Including file extensions: php
Processed 184820 lines contained in 1022 files.
Processing took 102.01615691185 seconds.

# nuance
#### C:\xampp\htdocs\wp-content\plugins\updraftplus\central\classes\class-automatic-upgrader-skin.php
* funcGetArg
 * Line 64: `			$args = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\central\commands.php
* funcGetArg
 * Line 28: `		$files = func_get_args();`
 * Line 38: `		$files = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\central\modules\comments.php
* foreachByReference
 * Line 290: `		foreach ($comments as &$comment) {`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\central\modules\users.php
* foreachByReference
 * Line 348: `		foreach ($users as &$user) {`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\class-updraftplus.php
* funcGetArg
 * Line 1038: `		$args = func_get_args();`
 * Line 2211: `		// func_get_arg() could not be used in parameter lists prior to PHP 5.3, so, we get it as a variable`
 * Line 2212: `		if (1 == $args && null !== ($first_arg = func_get_arg(0)) && is_array($first_arg)) {`
 * Line 2218: `				$key = func_get_arg($i*2-2);`
 * Line 2219: `				$value = func_get_arg($i*2-1);`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\includes\Google\Model.php
* funcGetArg
 * Line 39: `    if (func_num_args() == 1 && is_array(func_get_arg(0))) {`
 * Line 41: `      $array = func_get_arg(0);`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\includes\S3.php
* arrayValueByReference
 * Line 479: `		$input['fp'] =& $resource;`
 * Line 680: `				$input['type'] =& $requestHeaders['Content-Type'];`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\includes\cloudfiles\cloudfiles_http.php
* funcGetArg
 * Line 1355: `        $argv = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\includes\updraft-restorer-skin.php
* funcGetArg
 * Line 32: `			$args = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\aws\aws-sdk-php\src\Aws\S3\Iterator\ListBucketsIterator.php
* foreachByReference
 * Line 37: `            foreach ($buckets as &$bucket) {`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\guzzle\guzzle\src\Guzzle\Http\Curl\CurlHandle.php
* funcGetArg
 * Line 182: `                $args = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\guzzle\guzzle\src\Guzzle\Http\Message\Header\Link.php
* foreachByReference
 * Line 75: `        foreach ($links as &$link) {`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\guzzle\guzzle\src\Guzzle\Parser\UriTemplate\UriTemplate.php
* foreachByReference
 * Line 64: `        foreach ($values as &$value) {`
 * Line 166: `                        foreach ($kvp as $k => &$v) {`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\guzzle\guzzle\src\Guzzle\Plugin\Oauth\OauthPlugin.php
* foreachByReference
 * Line 258: `        foreach ($data as $key => &$value) {`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\guzzle\guzzle\src\Guzzle\Service\Builder\ServiceBuilderLoader.php
* foreachByReference
 * Line 17: `        foreach ($services as $name => &$service) {`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\guzzle\guzzle\src\Guzzle\Service\Command\LocationVisitor\Request\AbstractRequestVisitor.php
* foreachByReference
 * Line 40: `        foreach ($value as $name => &$v) {`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\guzzle\guzzle\src\Guzzle\Service\Command\LocationVisitor\Response\JsonVisitor.php
* foreachByReference
 * Line 52: `                foreach ($value as &$item) {`
 * Line 77: `                    foreach ($value as &$v) {`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\guzzle\guzzle\src\Guzzle\Service\Command\LocationVisitor\Response\XmlVisitor.php
* foreachByReference
 * Line 87: `        foreach ($value as &$item) {`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\guzzle\guzzle\src\Guzzle\Service\Description\SchemaValidator.php
* foreachByReference
 * Line 153: `            foreach ($value as $i => &$item) {`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\kriswallsmith\assetic\src\Assetic\Factory\Loader\FunctionCallsFormulaLoader.php
* funcGetArg
 * Line 32: `    $_call = func_get_args();`
 * Line 37: `    $_call = func_get_args();`
 * Line 42: `    $_call = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\phpseclib\phpseclib\phpseclib\Crypt\Base.php
* funcGetArg
 * Line 604: `                $func_args = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\phpseclib\phpseclib\phpseclib\Crypt\Hash.php
* funcGetArg
 * Line 823: `        $arguments = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\phpseclib\phpseclib\phpseclib\Crypt\RSA.php
* foreachByReference
 * Line 1471: `                foreach ($values as &$value) {`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\phpseclib\phpseclib\phpseclib\File\X509.php
* funcGetArg
 * Line 4372: `        $this->domains = func_get_args();`
 * Line 4384: `        $this->ipAddresses = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\phpseclib\phpseclib\phpseclib\Math\BigInteger.php
* hexadecimalString
 * Line 222: `     *    $a = new Math_BigInteger('0x32', 16); // 50 in base-16`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\phpseclib\phpseclib\phpseclib\Net\SFTP.php
* funcGetArg
 * Line 437: `        $args = func_get_args();`
 * Line 1058: `        $args = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\phpseclib\phpseclib\phpseclib\Net\SSH1.php
* funcGetArg
 * Line 1288: `        $args = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\phpseclib\phpseclib\phpseclib\Net\SSH2.php
* funcGetArg
 * Line 1898: `        $args = func_get_args();`
 * Line 1919: `        $args = array_slice(func_get_args(), 1);`
 * Line 2152: `        $responses = func_get_args();`
 * Line 3756: `        $args = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\symfony\process\InputStream.php
* yield
 * Line 65: `                yield '';`
 * Line 71: `                    yield $cur;`
 * Line 74: `                yield $current;`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\symfony\process\PhpProcess.php
* funcGetArg
 * Line 65: `        $env = 1 < \func_num_args() ? func_get_arg(1) : null;`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\symfony\process\Process.php
* funcGetArg
 * Line 186: `        $env = 1 < \func_num_args() ? func_get_arg(1) : null;`
 * Line 208: `        $env = 1 < \func_num_args() ? func_get_arg(1) : null;`
 * Line 239: `            $env = func_get_arg(1);`
 * Line 339: `        $env = 1 < \func_num_args() ? func_get_arg(1) : null;`
* yield
 * Line 515: `                    yield self::OUT => $out;`
 * Line 526: `                    yield self::ERR => $err;`
 * Line 530: `                yield self::OUT => '';`


# critical
#### C:\xampp\htdocs\wp-content\plugins\updraftplus\class-updraftplus.php
* deprecatedFunctions
 * Line 3190: `			if ('mysql link' == $type && @mysql_ping($handle)) return true;// phpcs:ignore Generic.PHP.NoSilencedErrors.Discouraged, PHPCompatibility.Extensions.RemovedExtensions.mysql_DeprecatedRemoved -- Needed to add this as the old ignores no longer work`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\includes\class-database-utility.php
* deprecatedFunctions
 * Line 85: `			$res = @mysql_query(sprintf($sql, mysql_real_escape_string($variable, $db_handle), mysql_real_escape_string($value, $db_handle)), $db_handle);`
 * Line 105: `			$res = @mysql_query(sprintf($sql, mysql_real_escape_string($variable, $db_handle)), $db_handle);`
 * Line 116: `			$res = mysql_result($res, 0);`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\restorer.php
* deprecatedFunctions
 * Line 1911: `				@mysql_query('SET SESSION query_cache_type = OFF;', $this->mysql_dbh);`
 * Line 1960: `				$req = mysql_unbuffered_query("CREATE TABLE $random_table_name (test INT)", $this->mysql_dbh);`
 * Line 1965: `				$this->last_error = $this->use_mysqli ? mysqli_error($this->mysql_dbh) : mysql_error($this->mysql_dbh);`
 * Line 1967: `				$this->last_error_no = $this->use_mysqli ? mysqli_errno($this->mysql_dbh) : mysql_errno($this->mysql_dbh);`
 * Line 1973: `					$reqtrigger = mysql_unbuffered_query("CREATE TRIGGER test_trigger BEFORE INSERT ON $random_table_name FOR EACH ROW SET @sum = @sum + NEW.test", $this->mysql_dbh);`
 * Line 2012: `					$req = mysql_unbuffered_query("DROP TABLE $random_table_name", $this->mysql_dbh);`
 * Line 2016: `					$this->last_error = ($this->use_mysqli) ? mysqli_error($this->mysql_dbh) : mysql_error($this->mysql_dbh);`
 * Line 2018: `					$this->last_error_no = ($this->use_mysqli) ? mysqli_errno($this->mysql_dbh) : mysql_errno($this->mysql_dbh);`
 * Line 2523: `				$req = mysql_unbuffered_query("LOCK TABLES $table WRITE;", $this->mysql_dbh);`
 * Line 2527: `				$lock_error_no = $this->use_mysqli ? mysqli_errno($this->mysql_dbh) : mysql_errno($this->mysql_dbh);`
 * Line 2546: `			$req = mysql_unbuffered_query("UNLOCK TABLES;");`
 * Line 2713: `					$req = mysql_unbuffered_query($sql_line, $this->mysql_dbh);`
 * Line 2715: `					if (!$req) $this->last_error = mysql_error($this->mysql_dbh);`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\phpseclib\phpseclib\phpseclib\Crypt\Base.php
* oldClassConstructors
 * Line 503: `    function Crypt_Base($mode = CRYPT_MODE_CBC)`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\phpseclib\phpseclib\phpseclib\Crypt\Hash.php
* oldClassConstructors
 * Line 183: `    function Crypt_Hash($hash = 'sha1')`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\phpseclib\phpseclib\phpseclib\Crypt\RC4.php
* oldClassConstructors
 * Line 163: `    function Crypt_RC4()`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\phpseclib\phpseclib\phpseclib\Crypt\RSA.php
* oldClassConstructors
 * Line 531: `    function Crypt_RSA()`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\phpseclib\phpseclib\phpseclib\Crypt\TripleDES.php
* oldClassConstructors
 * Line 218: `    function Crypt_TripleDES($mode = CRYPT_MODE_CBC)`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\phpseclib\phpseclib\phpseclib\File\ANSI.php
* oldClassConstructors
 * Line 184: `    function File_ANSI()`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\phpseclib\phpseclib\phpseclib\File\ASN1.php
* oldClassConstructors
 * Line 139: `    function File_ASN1_Element($encoded)`
 * Line 262: `    function File_ASN1()`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\phpseclib\phpseclib\phpseclib\File\X509.php
* oldClassConstructors
 * Line 1353: `    function File_X509()`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\phpseclib\phpseclib\phpseclib\Math\BigInteger.php
* oldClassConstructors
 * Line 475: `    function Math_BigInteger($x = 0, $base = 10)`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\phpseclib\phpseclib\phpseclib\Net\SCP.php
* oldClassConstructors
 * Line 141: `    function Net_SCP($ssh)`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\phpseclib\phpseclib\phpseclib\Net\SFTP.php
* oldClassConstructors
 * Line 423: `    function Net_SFTP($host, $port = 22, $timeout = 10)`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\phpseclib\phpseclib\phpseclib\Net\SSH1.php
* oldClassConstructors
 * Line 528: `    function Net_SSH1($host, $port = 22, $timeout = 10, $cipher = NET_SSH1_CIPHER_3DES)`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\phpseclib\phpseclib\phpseclib\Net\SSH2.php
* oldClassConstructors
 * Line 988: `    function Net_SSH2($host, $port = 22, $timeout = 10)`

#### C:\xampp\htdocs\wp-content\plugins\updraftplus\vendor\phpseclib\phpseclib\phpseclib\System\SSH\Agent.php
* oldClassConstructors
 * Line 155: `    function System_SSH_Agent_Identity($fsock)`
 * Line 356: `    function System_SSH_Agent($address = null)`

