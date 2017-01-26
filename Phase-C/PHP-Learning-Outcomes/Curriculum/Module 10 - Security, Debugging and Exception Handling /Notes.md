## Suggestions

### Knowledge Unit

- Multiple exceptions handling [RFC](https://wiki.php.net/rfc/multiple-catch)

#### Previously

try {

} catch (ExceptionType1 $e) {

} catch (ExceptionType1 $e) {

} catch (Exception $e) {

}

#### Present Day (PSR7)

try {

} catch (ExceptionType1 | ExceptionType1 | $e) {

} catch (Exception $e) {

}
