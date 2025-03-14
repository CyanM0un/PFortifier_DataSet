#  PFortifier_new_chains

We list the new chains discovered by PFortifier along with the datasets.

## 1

- Application: Yii 1.1.20
- call stack:

~~~
cdbcriteria#__wakeup
cmapiterator#current
cform#offsetSet
phpunit_extensions_selenium2testcase_element_select#__call
phpunit_extensions_selenium2testcase_element_select#newCommand
~~~

## 2

- Application: Yii 1.1.20
- PHPGGC colleted: https://github.com/ambionics/phpggc/tree/master/gadgetchains/Yii/RCE/2
- call stack:

~~~
WikiPublishTask#__destruct
Prophecy\Argument\Token\ExactValueToken#__toString
phpunit_extensions_selenium2testcase_element_select#__call
phpunit_extensions_selenium2testcase_element_select#newCommand
~~~

## 3

- Application: Yii 1.1.20
- PHPGGC colleted: https://github.com/ambionics/phpggc/tree/master/gadgetchains/Phing/FD/1
- call stack:

~~~
WikiPublishTask#__destruct
~~~

## 4

- Application: Yii 1.1.20
- call stack:

~~~
DocBlox_Parallel_WorkerPipe#__destruct
DocBlox_Parallel_WorkerPipe#release
~~~

## 5

- Application: PHPExcel (WP) 1.8.1
- call stack:

~~~
phpexcel_comment#__toString
phpexcel_richtext#getPlainText
requests_utility_filterediterator#current
~~~

## 6

- Application: PHPExcel (WP) 1.8.1
- call stack:

~~~
PHPExcel_CachedObjectStorage_SQLite#__destruct
PHPExcel_RichText#__toString
PHPExcel_RichText#getPlainText
requests_utility_filterediterator#current
~~~

## 7

- Application: PHPExcel (WP) 1.8.1
- call stack:

~~~
PHPExcel_CachedObjectStorage_Memcache#__destruct
PHPExcel_CachedObjectStorage_Memcache#getCellList
PHPExcel_CachedObjectStorage_Memcache#_storeData
PHPExcel_RichText#__toString
PHPExcel_RichText#getPlainText
requests_utility_filterediterator#current
~~~

## 8

- Application: PHPCSFixer 2.7.13
- call stack:

~~~
Keradus\CliExecutor\ScriptExecutor#__destruct
~~~

## 9

- Application: PHPCSFixer 2.7.13
- call stack:

~~~
PhpCsFixer\Cache\FileCacheManager#__destruct
PhpCsFixer\Cache\FileCacheManager#writeCache
PHPUnit\Util\Printer#write
~~~

## 10

- Application: CodeIgniter 4.1.3
- call stack:

~~~
CodeIgniter\\Cache\\Handlers\\RedisHandler#__destruct
CodeIgniter\\Session\Handlers\\DatabaseHandler#close
CodeIgniter\\Session\Handlers\DatabaseHandler#releaseLock
Symfony\Component\HttpFoundation\Request#__toString
Symfony\Component\HttpFoundation\Request#getMethod
Symfony\Component\Console\CommandLoader\ContainerCommandLoader#get
Symfony\Component\DependencyInjection\Argument\ServiceLocator#get
~~~

## 11

- Application: CodeIgniter 4.1.3
- PHPGGC colleted: https://github.com/ambionics/phpggc/tree/master/gadgetchains/CodeIgniter4/RCE/5
- call stack

~~~
Predis\Connection\StreamConnection#__destruct
CodeIgniter\Entity\Entity#__get
Symfony\Component\HttpFoundation\Request#__toString
Symfony\Component\HttpFoundation\Request#getMethod
Symfony\Component\DependencyInjection\Argument\ServiceLocator#get
~~~

## 12

- Application: CodeIgniter 4.1.3
- PHPGGC colleted: https://github.com/ambionics/phpggc/tree/master/gadgetchains/CodeIgniter4/RCE/6
- call stack:

~~~
Predis\Response\Iterator\MultiBulk#__destruct
Predis\Response\Iterator\MultiBulk#drop
Faker\ValidGenerator#__call
~~~

## 13

- Application: Slim 3.8.1
- call stack:

~~~
phpDocumentor\Reflection\DocBlock\Tags\Method#__toString
Slim\Container#offsetGet
Slim\DeferredCallable#__invoke
~~~

## 14

- Application: Slim 3.8.1
- call stack:

~~~
Prophecy\Argument\Token\ExactValueToken#__toString
Slim\App#__call
~~~

## 15

- Application: Slim 4.1.0
- call stack:

~~~
Prophecy\Argument\Token\ExactValueToken#__toString
AdrianSuter\Autoload\Override\ClosureHandler#__call
~~~

## 16

- Application: Spiral 2.8
- call stack:

~~~
App\App#__destruct
Cycle\Database\Driver\Postgres\Schema\PostgresColumn#__call
Cycle\Database\Driver\Postgres\Schema\PostgresColumn#type
Laminas\Hydrator\Iterator\HydratingIteratorIterator#current
Laminas\Hydrator\Strategy\ClosureStrategy#hydrate
~~~

## 17

- Application: Spiral 2.8
- call stack:

~~~
Spiral\Files\Files#__destruct
Spiral\Files\Files#delete
Spiral\Files\Files#exists
Laminas\Diactoros\RelativeStream#__toString
Laminas\Diactoros\RelativeStream#getContents
Laminas\Diactoros\CallbackStream#getContents
~~~

## 18

- Application: Spiral 2.8
- call stack:

~~~
Monolog\Handler\FingersCrossedHandler#__destruct
Monolog\Handler\FingersCrossedHandler#close
Monolog\Handler\FingersCrossedHandler#flushBuffer
Monolog\Handler\PsrHandler#handleBatch
Monolog\Handler\PsrHandler#handle
Spiral\Logger\NullLogger#log
~~~

## 19

- Application: Spiral 2.8
- call stack:

~~~
Monolog\Handler\RollbarHandler#__destruct
Monolog\Handler\RollbarHandler#close
Monolog\Handler\RollbarHandler#flush
PHPUnit\Runner\ResultCacheExtension#flush
PHPUnit\Runner\DefaultTestResultCache#persist
~~~

## 20

- Application: Spiral 2.8
- call stack:

~~~
App\App#__destruct
SebastianBergmann\CodeCoverage\Report\Xml\Coverage#finalize
Spiral\Http\\Request\InputManager#__get
Spiral\Http\\Request\InputManager#bag
Spiral\Http\Request\InputManager#request
Symfony\Component\Console\CommandLoader\FactoryCommandLoader#get
~~~

## 21

- Application: Spiral 2.8
- PHPGGC colleted: https://github.com/ambionics/phpggc/tree/master/gadgetchains/Spiral/RCE/1
- call stack:

~~~
Monolog\Handler\RotatingFileHandler#__destruct
Monolog\Handler\RotatingFileHandler#close
Monolog\Handler\RotatingFileHandler#rotate
Spiral\Reactor\FileDeclaration#__toString
Spiral\Reactor\FileDeclaration#render
PhpOption\LazyOption#isEmpty
PhpOption\LazyOption#option
~~~

## 22

- Application: Spiral 2.8
- PHPGGC colleted: https://github.com/ambionics/phpggc/tree/master/gadgetchains/Spiral/RCE/2
- call stack:

~~~
App\App#__destruct
Spiral\Boot\Finalizer#finalize
PhpOption\LazyOption#get
PhpOption\LazyOption#option
~~~

## 23

- Application: Swoft 2.0.11
- call stack:

~~~
Swoft\Session\SwooleStorage#__destruct
Swoft\Http\Session\HttpSession#destroy
Swoft\Http\Session\Handler\FileHandler#destroy
~~~

## 24

- Application: Swoft 2.0.11
- call stack:

~~~
Monolog\Handler\SyslogUdpHandler#__destruct
Monolog\Handler\SyslogUdpHandler#close
Swoft\Cache\Adapter\FileAdapter#close
Swoft\Cache\Adapter\FileAdapter#saveData
Swoft\Cache\Adapter\FileAdapter#doWrite
~~~

## 25

- Application: Swoft 2.0.11
- call stack:

~~~
Swoft\Session\SwooleStorage#__destruct
Symfony\Component\Cache\Traits\RedisProxy#__call
Swoole\ObjectProxy#__invoke"
~~~

## 26

- Application: Swoft 2.0.11
- call stack:

~~~
Monolog\Handler\RollbarHandler#__destruct
Monolog\Handler\RollbarHandler#close
Monolog\Handler\RollbarHandler#flush
PHPUnit\Runner\ResultCacheExtension#flush
PHPUnit\Runner\DefaultTestResultCache#persist
~~~

## 27

- Application: ThinkPHP 6.1.0
- PHPGGC colleted:https://github.com/ambionics/phpggc/tree/master/gadgetchains/ThinkPHP/RCE/3
- call stack:

~~~
League\Flysystem\Cached\Storage\Psr6Cache#__destuct
League\Flysystem\Cached\Storage\Psr6Cache#save
League\Flysystem\Directory#__call
think\Validate__#call
think\Validate__#is
~~~

## 28

- Application: ThinkPHP 6.1.0
- PHPGGC colleted:https://github.com/ambionics/phpggc/tree/master/gadgetchains/ThinkPHP/RCE/4
- call stack:

~~~
think\model\Pivot#__destruct
think\model\Pivot#save
think\model\Pivot#updateData
think\model\Pivot#db
think\model\concern\Conversion#__toString
think\model\concern\Conversion#toJson
think\model\concern\Conversion#toArray
think\model\concern\Attribute#getAttr
think\model\concern\Attribute#getValue
think\model\concern\Attribute#getJsonValue
~~~

## 29

- Application: ThinkPHP 6.1.0
- call stack:

~~~
League\Flysystem\Cached\Storage\Psr6Cache#__destruct
League\Flysystem\Cached\Storage\Psr6Cache#save
think\model\relation\HasMany#__call
think\model\relation\HasMany#baseQuery
think\model\Pivot#__isset
think\model\Pivot#getAttr
think\model\Pivot#getValue
think\model\Pivot#getJsonValue
~~~

## 30

- Application: ThinkPHP 6.1.0
- call stack:

~~~
League\Flysystem\Cached\Storage\Adapter#__destruct
League\Flysystem\Cached\Storage\Adapter#save
League\Flysystem\Adapter\Local#update
~~~

## 31

- Application: SwiftMailer 5.4.12
- call stack:

~~~
Swift_KeyCache_DiskKeyCache#__destruct
Swift_KeyCache_DiskKeyCache#clearAll
Swift_KeyCache_DiskKeyCache#clearKey
Swift_KeyCache_DiskKeyCache#unlink
~~~

## 32

- Application: SwiftMailer 5.4.12
- PHPGGC colleted:https://github.com/ambionics/phpggc/tree/master/gadgetchains/SwiftMailer/FD/2
- call stack:

~~~
Swift_Image#__destruct
Swift_KeyCache_DiskKeyCache#clearAll
Swift_KeyCache_DiskKeyCache#clearKey
~~~

## 33

- Application: SwiftMailer 6.0.0
- PHPGGC colleted:https://github.com/ambionics/phpggc/tree/master/gadgetchains/SwiftMailer/FR/1
- call stack:

~~~
Swift_EmbeddedFile#__toString
Swift_Mime_SimpleMimeEntity#toString
Swift_Mime_SimpleMimeEntity#bodyToString
Swift_Mime_SimpleMimeEntity#getBody
Swift_Mime_SimpleMimeEntity#readStream
Swift_ByteStream_FileByteStream#read
Swift_ByteStream_FileByteStream#getReadHandle
~~~

## 34

- Application: Monolog 1.7.0
- call stack:

~~~
Monolog\Handler\AbstractHandler#__destruct
Monolog\Handler\RotatingFileHandler#close
Monolog\Handler\RotatingFileHandler#rotate
Monolog\Handler\RotatingFileHandler#unlink
~~~

## 35

- Application: Monolog 1.18.0
- call stack:

~~~
Monolog\Handler\AbstractHandler#__destruct
Monolog\Handler\FingersCrossedHandler#close
Monolog\Handler\MailHandler#handleBatch
Monolog\Handler\NativeMailerHandler#send
Monolog\Handler\NativeMailerHandler#mail
~~~

## 36

- Application: Monolog 2.0.0
- call stack:

~~~
Monolog\Handler\FingersCrossedHandler#__destruct
Monolog\Handler\FingersCrossedHandler#close
Monolog\Handler\FingersCrossedHandler#flushBuffer
Monolog\Handler\ProcessHandler#handleBatch
Monolog\Handler\ProcessHandler#handle
Monolog\Handler\ProcessHandler#write
Monolog\Handler\ProcessHandler#ensureProcessIsStarted
Monolog\Handler\ProcessHandler#startProcess
~~~

## 37

- Application: Monolog 2.0.0
- call stack:

~~~
Monolog\Handler\DeduplicationHandler#__destruct
Monolog\Handler\DeduplicationHandler#close
Monolog\Handler\DeduplicationHandler#flush
Monolog\Handler\DeduplicationHandler#appendRecord
~~~

## 38

- Application: ZendFramework 1.12.20
- call stack:

~~~
simpleProcess#__destruct
simpleProcess#stop
simpleProcess#_cleanProcessContext
~~~

## 39

- Application: ZendFramework 1.12.20
- call stack:

~~~
Zend_Ldap_Node#__wakeup
Zend_Ldap_Node#detachLdap
Zend_Service_Twitter#__call
Zend_Form#__toString
Zend_Form#render
Zend_Form#getDecorators
Zend_Form#_loadDecorator
Zend_Form#_getDecorator
Zend_Loader_PluginLoader#load
~~~

## 40

- Application: ZendFramework 1.12.20
- call stack:

~~~
Zend_Gdata_App_LoggingHttpClientAdapterSocket#__destruct
Zend_Gdata_App_LoggingHttpClientAdapterSocket#close
Zend_Gdata_App_LoggingHttpClientAdapterSocket#log
Zend_Dojo_View_Helper_Dojo_Container#__toString
Zend_Dojo_View_Helper_Dojo_Container#_renderExtras
Zend_View#escape
~~~

## 41

- Application: ZendFramework 1.12.20
- call stack:

~~~
Zend_Gdata_App_LoggingHttpClientAdapterSocket#__destruct
Zend_Gdata_App_LoggingHttpClientAdapterSocket#close
Zend_Tag_Cloud#__toString
Zend_Form_Decorator_Callback#render
~~~

## 42

- Application: ZendFramework 1.12.20
- call stack:

~~~
Zend_Memory_Manager#__destruct
Zend_Log#__call
Zend_Log#log
Zend_CodeGenerator_Php_File#write
~~~

## 43

- Application: POPPHP 4.7.0
- call stack:

~~~
Pop\Mail\Transport\Smtp\Stream\Byte\TemporaryFileByteStream#__destruct
~~~

## 44

- Application: POPPHP 4.7.0
- call stack:

~~~
Pop\Mail\Transport\Smtp\Stream\Byte\TemporaryFileByteStream#__destruct
Pop\Image\Adapter\Imagick#__toString
~~~

## 45

- Application: CakePHP 3.9.6
- call stack:

~~~
Symfony\Component\Process\Process#__destruct
Phinx\Config\Config#offsetGet
Cake\I18n\ChainMessagesLoader#__invoke
Cake\Collection\Iterator\ReplaceIterator#current
~~~

## 46

- Application: CakePHP 3.9.6
- call stack:

~~~
Symfony\Component\Process\Pipes\UnixPipes#__destruct
Symfony\Component\Process\Pipes\UnixPipes#close
Cake\\Database\Statement\BufferedStatement#valid
Cake\\Database\Statement\BufferedStatement#fetch
Cake\Database\Statement\CallbackStatement#fetch
~~~

## 47

- Application: CakePHP 3.9.6
- call stack:

~~~
Symfony\Component\Process\Pipes\UnixPipes#__destruct
Symfony\Component\Process\Pipes\UnixPipes#close
PharIo\Manifest\ExtElementCollection#valid
App\Shell\ConsoleShell#__get
Twig\Cache\FilesystemCache#load
~~~

## 48

- Application: CakePHP 3.9.6
- call stack:

~~~
Cake\Cache\Engine\RedisEngine#__destruct
Phin\Config\Config#offsetGet
Cake\I18n\ChainMessagesLoader#__invoke
Cake\Collection\Iterator\ReplaceIterator#current
~~~

## 49

- Application: Typo3 9.3.0
- call stack:

~~~
TYPO3\CMS\\Extensionmanager\Controller\UploadExtensionFileController#__destruct
TYPO3\CMS\Extensionmanager\Controller\UploadExtensionFileController#removeBackupFolder
TYPO3\CMS\Core\Utility\\GeneralUtility#rmdir
TYPO3\CMS\Backend\Template\Components\Buttons\InputButton#__toString
TYPO3\CMS\Backend\Template\Components\Buttons\InputButton#render
TYPO3\CMS\Fluid\ViewHelpers\TranslateViewHelper#render
TYPO3\CMS\Fluid\ViewHelpers\TranslateViewHelper#renderChildren
~~~

## 50

- Application: Typo3 9.3.0
- call stack:

~~~
TYPO3\CMS\Extbase\Reflection\ReflectionService#__destruct
TYPO3\CMS\Core\Cache\\Backend\FileBackend#set
TYPO3\CMS\Core\Cache\\Backend\FileBackend#remove
~~~

## 51

- Application: Omnipay 3.0.0
- call stack:

~~~
GuzzleHttp\Cookie\FileCookieJar#__destruct
GuzzleHttp\Cookie\FileCookieJar#save
Symfony\Component\HttpFoundation\Request#__toString
Symfony\Component\HttpFoundation\Request#getMethod
Symfony\Component\HttpFoundation\Session\Session#get
Symfony\Component\HttpFoundation\Session\Session#getAttributeBag
Symfony\Component\HttpFoundation\Session\Session#getBag
Symfony\Component\HttpFoundation\Session\SessionBagProxy#getBag
~~~

## 52

- Application: Laminas 2.11.2
- call stack:

~~~
laminas\http\response\stream#__destruct
laminas\uri\mailto#__toString
laminas\uri\mailto#toString
laminas\uri\mailto#isValid
laminas\validator\callback#isValid
~~~

## 53

- Application: Guzzle (WP) 4.0.0 <= 6.4.1+
- call stack:

~~~
guzzlehttp\psr7\appendstream#__toString
guzzlehttp\psr7\appendstream#rewind
guzzlehttp\psr7\appendstream#seek
requests_utility_filterediterator#current
~~~

## 54

- Application: Yii 2.0.37
- call stack:

~~~
yii\db\BatchQueryResult#__destruct
Faker\ValidGenerator#__call
~~~

## 55

- Application: Yii 2.0.37
- call stack:

~~~
Swift_KeyCache_DiskKeyCache#__destruct
Swift_KeyCache_DiskKeyCache#clearAll
Symfony\Component\DomCrawler\Form#offsetGet
Symfony\Component\Console\CommandLoader\FactoryCommandLoader#get
~~~

## 56

- Application: Yii 2.0.37
- call stack:

~~~
yii\db\BatchQueryResult#__destruct
yii\db\BatchQueryResult#reset
Prophecy\Prophecy\ObjectProphecy#__call
Prophecy\Prophecy\ObjectProphecy#getMethodProphecies
Symfony\Component\DomCrawler\Form#offsetGet
Symfony\Component\Console\CommandLoader\FactoryCommandLoader#get
~~~
