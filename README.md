# Regex Snippets

A VS Code Extension with a list of 50+ hand picked Regex Codes made as a part of an Egghead Challenge.

### Why This Extension?
When the challenge was announced and the topics were told, I saw Regex on the list and thought "Oh, there will already be 100s of extensions out there for Regex Snippets". Well, I was wrong. I did not find even a single extension for the same so decided to take this up.

### Snippets

The following table shows all the 50+ code snippets included within this extension

| Sl No.| Prefix | Description | Input Required |
| ----------- | ----------- | ----------- | ----------- |
| 1     | `!valemail` | Email Address Validation | N/A
| 2  | `!valhexcol` | Hexadecimal Color Validation | N/A
| 3  | `!valpass` | Password Validation (1 uppercase,1 lowercase, 1 number, 1 special) | 2 Inputs: `min` and `max` length for the password
| 4  | `!valisbn` | ISBN Number Validation | N/A
| 5  | `!valipv4` | IPV4 Address Validation | N/A
| 6  | `!valipv6` | IPV6 Address Validation | N/A
| 7  | `!valmmddyy` | Date Validation In mm/dd/yy format (Separator Does Not Matter) | N/A
| 8  | `!valmonddyyyy` | Date Validation In mon/dd/yyyy format (Ex: Jan/23/2001, Separator does not matter) | N/A
| 9  | `!valmonth` | Month Validation (Both Full and Abbreviated Form, Ex: Jan(uary))| N/A
| 10  | `!extprice` | Extract Price Value from any string | 1 Input: `currency_symbol` for the currency you want to use
| 11  | `!parehead` | Parse an Email Header to retrieve "To" address | N/A
| 12 | `!valfbllink` | Check if the give Facebook Profile Link is valid | N/A
| 13 | `!valcc` | Credit Card Validation (Does not check for fake numbers) Supported Cards: Visa, MasterCard, American Express, Diners Club, Discover, and JCB | N/A
| 14 | `!valusername` | Username Validation with minimum and maximum characters | 2 inputs: `MIN_CHARS` and `MAX_CHARS`
| 15 | `!exturl` | Extract URLs from a string | N/A
| 16 | `!getiever` | Get the current Internet Explorer Version being used | N/A
| 17 | `!valimage` | Validate image filenames (Remove/ADD extensions as required) | N/A
| 18 | `!valcityabbr` | Validate City Names (Or any words) with First 2 letters abbreviated (Ex: India, IN) | N/A
| 19 | `!valusphone` | US Phone Number Validation | N/A
| 20 | `!valssn` | Social Security Number Validation | N/A
| 21 | `!valhtmlcont` | Verify if the given string contains content between the provided html tags (Ex: `<p>Hello</p>`) | 1 input: `tag_name` for the HTML Tag you want to search for
| 22 | `!valhtmltag` | Validates if the given string has either a opening or closing HTML tag (Does not verify if the HTML Tag exists) | N/A
| 23 | `!valtwitter` | Twitter Username Validation | N/A
| 24 | `!valurl` | URL Validation | N/A
| 25 | `!valgooglesyn` | Google Search Syntax Validation | N/A
| 26 | `!extcssmedia` | Extract properties and values from CSS Media Queries | N/A
| 27 | `!exthtmlcomms` | Strip all comments from a HTML Code Block | N/A
| 28 | `!extcss` | Extract Individual CSS Properties from the given Code Block | N/A
| 29 | `!extytid` | Extract Video ID from a valid Youtube Video Link | N/A
| 30 | `!extimgsrc` | Extract image source links from HTML Image Tags | N/A
| 31 | `!valbase64` | Base64 String Validation | N/A
| 32 | `!septhousand` | Seperates the digits in the string to thousand with commas | N/A
| 33 | `!valchars` | Validate if the the string contains atleast one occurrence of the Character to be searched | 1 Input: `chars_to_be_searched`
| 34 | `!valspaces` | Convert multiple spaces to single spaces between each word in a string | N/A
| 35 | `!extsqrbracks` | Extract Square Brackets and the content between them | N/A
| 36 | `!valalpnum` | Non-Alphanumeric Characters Validation | N/A
| 37 | `!extlogs` | Extract native Javascript console and AngularJS $log log warn or info that are NOT comments / commented out | N/A
| 38 | `!extbrackscont` | Extract all brackets and the content between them | N/A
| 39 | `!addlinktag` | Adds Link Tags to all the strings that start with http or https (Full Function Provided) | N/A
| 40 | `!findocurrences` | Provides a function to calculate the number of times the provided character(s) have appeared in the string (Returns 0 when no ocurrences found) | 2 Inputs: `string` on which the match should be applied and `string_to_search` for the string to be searched for
| 41 | `!valuuidv1` | UUID v1 Validation | N/A
| 42 | `!valuuidv2` | UUID v2 Validation | N/A
| 43 | `!valuuidv3` | UUID v3 Validation | N/A
| 44 | `!valuuidv4` | UUID v4 Validation | N/A
| 45 | `!valuuidv5` | UUID v5 Validation | N/A
| 46 | `!extquotes` | Extracts any text between quotations (Works with nested quotes too) | N/A
| 47 | `!splitnchunks` | Splits the given string to n-sized chunks even if its size is not an exact multiple | 1 Input: `end_size` for chunk size
| 48 | `!valzip` | Zip Code(5 or 9 digits only) Validation | N/A
| 49 | `!valendswith` | Check if the provided string ends with the given Character | 1 Input: `character` which the string should end with
| 50 | `!extdomain` | Extract the domain from a valid URL string | N/A
| 51 | `!tocamel` | Returns a function which converts the given string to camelCase | 1 Input: `string` to be replaced

### Author
Monish Basaniwal
