# example
--
    import "github.com/robertkrimen/godocdown/example"

Package example is an example package with documentation

	// Here is some code
	func example() {
		abc := 1 + 1
	}()

### Installation

	# This is how to install it:
	$ curl http://example.com
	$ tar xf example.tar.gz -C .
	$ ./example &

## Usage

```go
const (
	Another = 0
	Again   = "this"
)
```
Another constant section

```go
const Other = 3
```
A constant section

```go
var (
	This = 1

	// A description of That
	That = 2.1
)
```
A variable section

#### func  Example

```go
func Example()
```
Example is a function that does nothing

#### type ExampleType

```go
type ExampleType struct {
	First  int
	Second string
	Third  float64
	Parent *ExampleType
}
```

ExampleType is a type of nothing

    // Here is how to use it:
    return &ExampleType{
    	First: 1,
    	Second: "second",
    	nil,
    }

#### func  NewExample

```go
func NewExample() *ExampleType
```

#### func (ExampleType) Set

```go
func (ExampleType) Set() bool
```

--
**godocdown** http://github.com/robertkrimen/godocdown

--
This was via template
