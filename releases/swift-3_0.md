Swift 3.0 - Released on September 13, 2016
Swift 3 focused on solidifying and maturing the Swift language and development experience. It focused on several areas:

API design guidelines: The way in which Swift is used in popular libraries has almost as much of an effect on the character of Swift code as the Swift language itself. The API naming and design guidelines are a carefully crafted set of guidelines for building great Swift APIs.

Automatic application of naming guidelines to imported Objective-C APIs: When importing Objective-C APIs, the Swift 3 compiler automatically maps methods into the new Swift 3 naming guidelines, and provides a number of Objective-C features to control and adapt this importing.

Adoption of naming guidelines in key APIs: The Swift Standard Library has been significantly overhauled to embrace these guidelines, and key libraries like Foundation and libdispatch have seen major updates, which provide the consistent development experience we seek.

Swiftification of imported Objective-C APIs: Beyond the naming guidelines, Swift 3 provides an improved experience for working with Objective-C APIs. This includes importing Objective-C generic classes, providing the ability to import C APIs into an "Object Oriented" style, much nicer imported string enums, safer syntax to work with selectors and keypaths, etc.

Focus and refine the language: Since Swift 3 is the last release to make major source breaking changes, it is also the right release to reevaluate the syntax and semantics of the core language. This means that some obscure or problematic features will be removed, we focus on improving consistency of syntax in many small ways (e.g. by revising handling of parameter labels, and focus on forward looking improvements to the type system. This serves the overall goal of making Swift a simpler, more predictable, and more consistent language over the long term.

Swift 3 is the first release to enable broad scale adoption across multiple platforms, including significant functionality in the Swift core libraries (Foundation, libdispatch, XCTest, etc), portability to a number of platforms including Linux/x86, Raspberry Pi, and Android, and the Swift package manager to easily manage the distribution of Swift source code.

Finally, Swift 3 also includes a mix of relatively small but important additions to the language and standard library that make solving common problems easier and make everything feel nicer.

Evolution proposals included in Swift 3.0
SE-0002: Removing currying func declaration syntax
SE-0003: Removing var from Function Parameters
SE-0004: Remove the ++ and -- operators
SE-0005: Better Translation of Objective-C APIs Into Swift
SE-0006: Apply API Guidelines to the Standard Library
SE-0007: Remove C-style for-loops with conditions and incrementers
SE-0008: Add a Lazy flatMap for Sequences of Optionals
SE-0016: Adding initializers to Int and UInt to convert from UnsafePointer and UnsafeMutablePointer
SE-0017: Change Unmanaged to use UnsafePointer
SE-0019: Swift Testing
SE-0023: API Design Guidelines
SE-0025: Scoped Access Level
SE-0029: Remove implicit tuple splat behavior from function applications
SE-0031: Adjusting inout Declarations for Type Decoration
SE-0032: Add first(where:) method to SequenceType
SE-0033: Import Objective-C Constants as Swift Types
SE-0034: Disambiguating Line Control Statements from Debugging Identifiers
SE-0035: Limiting inout capture to @noescape contexts
SE-0036: Requiring Leading Dot Prefixes for Enum Instance Member Implementations
SE-0037: Clarify interaction between comments & operators
SE-0038: Package Manager C Language Target Support
SE-0039: Modernizing Playground Literals
SE-0040: Replacing Equal Signs with Colons For Attribute Arguments
SE-0043: Declare variables in 'case' labels with multiple patterns
SE-0044: Import as Member
SE-0046: Establish consistent label behavior across all parameters including first labels
SE-0047: Defaulting non-Void functions so they warn on unused results
SE-0048: Generic Type Aliases
SE-0049: Move @noescape and @autoclosure to be type attributes
SE-0052: Change IteratorType post-nil guarantee
SE-0053: Remove explicit use of let from Function Parameters
SE-0054: Abolish ImplicitlyUnwrappedOptional type
SE-0055: Make unsafe pointer nullability explicit using Optional
SE-0057: Importing Objective-C Lightweight Generics
SE-0059: Update API Naming Guidelines and Rewrite Set APIs Accordingly
SE-0060: Enforcing order of defaulted parameters
SE-0061: Add Generic Result and Error Handling to autoreleasepool()
SE-0062: Referencing Objective-C key-paths
SE-0063: SwiftPM System Module Search Paths
SE-0064: Referencing the Objective-C selector of property getters and setters
SE-0065: A New Model For Collections and Indices
SE-0066: Standardize function type argument syntax to require parentheses
SE-0067: Enhanced Floating Point Protocols
SE-0069: Mutability and Foundation Value Types
SE-0070: Make Optional Requirements Objective-C-only
SE-0071: Allow (most) keywords in member references
SE-0072: Fully eliminate implicit bridging conversions from Swift
SE-0076: Add overrides taking an UnsafePointer source to non-destructive copying methods on UnsafeMutablePointer
SE-0077: Improved operator declarations
SE-0081: Move where clause to end of declaration
SE-0085: Package Manager Command Names
SE-0086: Drop NS Prefix in Swift Foundation
SE-0088: Modernize libdispatch for Swift 3 naming conventions
SE-0089: Renaming String.init<T>(_: T)
SE-0091: Improving operator requirements in protocols
SE-0092: Typealiases in protocols and protocol extensions
SE-0093: Adding a public base property to slices
SE-0094: Add sequence(first:next:) and sequence(state:next:) to the stdlib
SE-0095: Replace protocol<P1,P2> syntax with P1 & P2 syntax
SE-0096: Converting dynamicType from a property to an operator
SE-0099: Restructuring Condition Clauses
SE-0101: Reconfiguring sizeof and related functions into a unified MemoryLayout struct
SE-0102: Remove @noreturn attribute and introduce an empty Never type
SE-0103: Make non-escaping closures the default
SE-0106: Add a macOS Alias for the OSX Platform Configuration Test
SE-0107: UnsafeRawPointer API
SE-0109: Remove the Boolean protocol
SE-0111: Remove type system significance of function argument labels
SE-0112: Improved NSError Bridging
SE-0113: Add integral rounding functions to FloatingPoint
SE-0114: Updating Buffer "Value" Names to "Header" Names
SE-0115: Rename Literal Syntax Protocols
SE-0116: Import Objective-C id as Swift Any type
SE-0117: Allow distinguishing between public access and public overridability
SE-0118: Closure Parameter Names and Labels
SE-0120: Revise partition Method Signature
SE-0121: Remove Optional Comparison Operators
SE-0124: Int.init(ObjectIdentifier) and UInt.init(ObjectIdentifier) should have a bitPattern: label
SE-0125: Remove NonObjectiveCBase and isUniquelyReferenced
SE-0127: Cleaning up stdlib Pointer and Buffer Routines
SE-0128: Change failable UnicodeScalar initializers to failable
SE-0129: Package Manager Test Naming Conventions
SE-0130: Replace repeating Character and UnicodeScalar forms of String.init
SE-0131: Add AnyHashable to the standard library
SE-0133: Rename flatten() to joined()
SE-0134: Rename two UTF8-related properties on String
SE-0135: Package Manager Support for Differentiating Packages by Swift version
SE-0136: Memory Layout of Values
SE-0137: Avoiding Lock-In to Legacy Protocol Designs
