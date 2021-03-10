2021-03-10T14:22:12+01:00
Scanning C:\xampp\htdocs\wp-content\plugins\w3-total-cache
Including file extensions: php
Processed 185787 lines contained in 1132 files.
Processing took 108.77387309074 seconds.

# critical
#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\ConfigDbStorage.php
* deprecatedFunctions
 * Line 180: `				$this->dbh = mysql_connect( $this->dbhost, $this->dbuser, $this->dbpassword, $new_link, $client_flags );`
 * Line 182: `				$this->dbh = @mysql_connect( $this->dbhost, $this->dbuser, $this->dbpassword, $new_link, $client_flags );`
 * Line 199: `			$success = mysql_select_db( $db, $dbh );`
 * Line 229: `			return mysql_real_escape_string( $string, $this->dbh );`
 * Line 257: `				$this->last_error = mysql_error( $this->dbh );`
 * Line 276: `			while ( $row = mysql_fetch_object( $this->result ) ) {`
 * Line 291: `			$this->result = mysql_query( $query, $this->dbh );`
 * Line 301: `			$closed = mysql_close( $this->dbh );`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Db\mssql.php
* deprecatedFunctions
 * Line 485: `                                mysql_set_charset( $this->charset, $this->dbh );`
 * Line 662: `         * Real escape, using mysql_real_escape_string() or addslashes()`
 * Line 664: `         * @see mysql_real_escape_string()`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Nusoap\class.soap_transport_http.php
* deprecatedFunctions
 * Line 515: `			//set_magic_quotes_runtime(0);`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Nusoap\nusoap.php
* deprecatedFunctions
 * Line 2584: `			//set_magic_quotes_runtime(0);`


# nuance
#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\ConfigDbStorage.php
* funcGetArg
 * Line 209: `		$args = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\DbCache_WpdbLegacy.php
* funcGetArg
 * Line 103: `		$args = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Aws\Aws\ClientSideMonitoring\ConfigurationProvider.php
* funcGetArg
 * Line 95: `        $links = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Aws\Aws\CommandPool.php
* yield
 * Line 60: `                    yield $key => $client->executeAsync($command);`
 * Line 62: `                    yield $client->executeAsync($command);`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Aws\Aws\Credentials\CredentialProvider.php
* funcGetArg
 * Line 100: `        $links = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Aws\Aws\Credentials\InstanceProfileProvider.php
* yield
 * Line 50: `            yield new Credentials(`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Aws\Aws\EndpointDiscovery\ConfigurationProvider.php
* funcGetArg
 * Line 90: `        $links = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Aws\Aws\MockHandler.php
* funcGetArg
 * Line 44: `        foreach (func_get_args() as $value) {`
 * Line 60: `        foreach (func_get_args() as $value) {`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Aws\Aws\ResultPaginator.php
* yield
 * Line 69: `                    yield Promise\promise_for($retVal);`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Aws\Aws\S3\BatchDelete.php
* yield
 * Line 101: `                        yield $promise;`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Aws\Aws\S3\MultipartCopy.php
* yield
 * Line 100: `                yield $command;`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Aws\Aws\S3\ObjectCopier.php
* yield
 * Line 91: `                yield $mup->promise();`
 * Line 100: `                yield $this->client->executeAsync(`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Aws\Aws\S3\S3MultiRegionClient.php
* yield
 * Line 239: `                        yield $handler($command);`
 * Line 255: `                        yield $handler($command);`
 * Line 264: `                                yield $handler($command);`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Aws\Aws\Waiter.php
* yield
 * Line 96: `                    yield $command;`
 * Line 102: `                    yield new RejectedPromise(new \RuntimeException($msg));`
 * Line 107: `                    yield new RejectedPromise(new \RuntimeException(`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Aws\Aws\functions.php
* yield
 * Line 32: `            yield $value;`
 * Line 47: `        yield $f($value);`
 * Line 64: `            yield $inner;`
 * Line 82: `            yield $buffer;`
 * Line 87: `        yield $buffer;`
 * Line 169: `        yield $file;`
 * Line 199: `            yield $fullPath;`
* funcGetArg
 * Line 105: `    $fns = func_get_args();`
 * Line 107: `        $args = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Aws\GuzzleHttp\Handler\CurlFactory.php
* funcGetArg
 * Line 415: `                $args = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Aws\GuzzleHttp\Handler\MockHandler.php
* funcGetArg
 * Line 119: `        foreach (func_get_args() as $value) {`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Aws\GuzzleHttp\Handler\StreamHandler.php
* funcGetArg
 * Line 437: `                $passed = func_get_args();`
 * Line 462: `            $args = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Aws\GuzzleHttp\Pool.php
* yield
 * Line 52: `                    yield $key => $client->sendAsync($rfn, $opts);`
 * Line 54: `                    yield $key => $rfn($opts);`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Aws\GuzzleHttp\Psr7\functions.php
* funcGetArg
 * Line 279: `            func_get_args()[1]`
* foreachByReference
 * Line 796: `    foreach ($keys as &$key) {`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Aws\GuzzleHttp\UriTemplate.php
* foreachByReference
 * Line 152: `                        foreach ($kvp as $k => &$v) {`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Aws\JmesPath\TreeCompiler.php
* funcGetArg
 * Line 73: `        $this->source .= vsprintf($str, array_slice(func_get_args(), 1)) . "\n";`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Azure\GuzzleHttp\Handler\CurlFactory.php
* funcGetArg
 * Line 387: `                $args = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Azure\GuzzleHttp\Handler\MockHandler.php
* funcGetArg
 * Line 107: `        foreach (func_get_args() as $value) {`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Azure\GuzzleHttp\Handler\StreamHandler.php
* funcGetArg
 * Line 402: `                $passed = func_get_args();`
 * Line 427: `            $args = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Azure\GuzzleHttp\Pool.php
* yield
 * Line 52: `                    yield $key => $client->sendAsync($rfn, $opts);`
 * Line 54: `                    yield $key => $rfn($opts);`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Azure\GuzzleHttp\Psr7\functions.php
* funcGetArg
 * Line 275: `            func_get_args()[1]`
* foreachByReference
 * Line 742: `    foreach ($keys as &$key) {`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Azure\GuzzleHttp\UriTemplate.php
* foreachByReference
 * Line 152: `                        foreach ($kvp as $k => &$v) {`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Azure\MicrosoftAzureStorage\Common\Internal\ConnectionStringParser.php
* funcGetArg
 * Line 175: `        $arguments = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Azure\MicrosoftAzureStorage\Common\Internal\ServiceRestProxy.php
* yield
 * Line 205: `                    yield $sendAsync($request);`
 * Line 208: `                    yield $sendAsync($request);`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Azure\MicrosoftAzureStorage\Common\Internal\ServiceSettings.php
* funcGetArg
 * Line 163: `        $allSettings = func_get_args();`
 * Line 174: `        $optionalSettings = func_get_args();`
 * Line 185: `        $requiredSettings = func_get_args();`
 * Line 216: `        $validValues = func_get_args();`
 * Line 264: `        $constraints = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Azure\MicrosoftAzureStorage\Common\Internal\Utilities.php
* funcGetArg
 * Line 143: `        $arguments    = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Db\mssql.php
* funcGetArg
 * Line 772: `                $this->prepare_args = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Google\Model.php
* funcGetArg
 * Line 36: `    if (func_num_args() == 1 && is_array(func_get_arg(0))) {`
 * Line 38: `      $array = func_get_arg(0);`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\Minify\JSMinPlus.php
* funcGetArg
 * Line 1423: `			$args = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\S3Compatible.php
* arrayValueByReference
 * Line 387: `				$input['type'] =& $requestHeaders['Content-Type'];`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\lib\SNS\sdk.class.php
* funcGetArg
 * Line 761: `		$method_arguments = func_get_args();`

#### C:\xampp\htdocs\wp-content\plugins\w3-total-cache\w3-total-cache-api.php
* funcGetArg
 * Line 576: `	$args = func_get_args();`

