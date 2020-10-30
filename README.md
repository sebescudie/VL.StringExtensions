# VL.StringExtensions

_This plugin is a VL wrapper for [Jeff Klein's String.Extensions](https://github.com/Jeff-Klein/String.Extensions) and [monk8800's StringExtensions](https://github.com/monk8800/StringExtensions) .NET libraries. The plugin exposes some of their methods as VL nodes._

## Usage

- In VL's Quad Menu, go to Dependencies/Manage Nugets/Commandline and type `nuget install VL.StringExtensions`. The nodes will be available in the nodebrowser under in the String category.

## What's inside

The nodes were separated into distinct categories to help you find what you're looking for. For each of those categories, you get an overview patch with all the nodes in action.

### Verification

Allows to check things about a string

- `IsEmailAddress`
- `IsInteger`
- `IsNull`
- `IsNumeric`
- `IsValidIPV4`
- `IsAlpha`
- `IsAlphaNumeric`
- `IsDateTime`
- `DoesNotStartWith`
- `DoesNotEndWith`
- `EndsWithIgnoreCase`
- `StartsWithIgnoreCase`

### Extraction

Extracts parts of a string

- `FirstCharacter`
- `LastCharacter`
- `Left`
- `Right`
- `CountOccurrences`
- `GetByteSize`

### Modification

Modifies the input string

- `AppendPrefixIfMissing`
- `AppendSuffixIfMissing`
- `ReplaceLineFeeds`
- `Reverse`
- `ReverseSlash`
- `SplitTo`
- `Replace`
- `RemoveAllAlphabeticalLetters`
- `RemoveAllSpecialCharacters`
- `RemoveAllNumbers`
- `KeepAllSpecialCharacters`
- `KeepOnlyAlphabeticalLetters`
- `KeepOnlyNumbers`
- `Truncate`
- `RemoveChars`
- `RemovePrefix`
- `RemoveSuffix`

### Encryption

- `Encrypt`
- `Decrypt`
- `CreateHashSha256`
- `CreateHashSha512`

### Fallback

- `GetDefaultIfEmpty`
- `GetEmptyStringIfNull`
- `GetNullIfEmptyString`