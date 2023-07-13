# Extension VSCode for Go (Golang)

[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/UmarMarufMutaqin.go-snippets-simple?logo=visualstudio)](https://marketplace.visualstudio.com/items?itemName=UmarMarufMutaqin.go-snippets-simple)
[![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/UmarMarufMutaqin.go-snippets-simple?logo=visualstudio)](https://marketplace.visualstudio.com/items?itemName=UmarMarufMutaqin.go-snippets-simple)
[![Visual Studio Marketplace Downloads](https://img.shields.io/visual-studio-marketplace/d/UmarMarufMutaqin.go-snippets-simple?logo=visualstudio)](https://marketplace.visualstudio.com/items?itemName=UmarMarufMutaqin.go-snippets-simple)

This extension provides Go (Golang) code snippets that can be used in your Go projects. Snippets are pre-defined code snippets that can be automatically inserted using specific keywords.

## Key Features

- Go (Golang) Code Snippets: This extension provides various code snippets commonly used in Go development, such as basic program structure, functions, variables, loops, and more. You can save time and effort by using these snippets instead of rewriting the same code repeatedly.

## How to Use Snippets

![screenshot](https://raw.githubusercontent.com/takahashiumaru/go-snippets/main/image.png)

1. Make sure you have installed this extension in VSCode.
2. Open the Go file where you want to add code snippets.
3. Type the keyword of the snippet you want to use.
4. To select a snippet, start by typing an exclamation mark (!) followed by the keyword or description of the snippet you want to insert. For example, if you want to insert a snippet for a function declaration, you can type "!function" or "!func". This will display a list of matching snippets, and you can choose the one you want by pressing Tab or using the cursor to select it.
5. The Go code snippet will be added to the editor instantly.

## Available Snippets

- `!time`: Show `time.Now()`
- `!timeUnix`: Show `time.Now().Unix()`
- `!timeMonthString`: Show `time.Now().Format("200601")`
- `!timeDateString`: Show `time.Now().Format("20060102")`
- `!convStringToInt`: Show `int, err := strconv.Atoi(?)`
- `!convStringToUint`: Show `uint, err := strconv.ParseUint(?, 10, 32)`
- `!convStringToFloat`: Show `float, err := strconv.ParseFloat(?, 8)`
- `!convFloatToString`: Show `strconv.FormatFloat(?, 'f', -1, 64)`
- `!convUintToString`: Show `strconv.FormatUint(uint64(?), 10)`
- `!convFloatToString`: Show `uint, err := strconv.ParseUint(?, 10, 32)`
- `!fmtSring`: Show `%s` To Complate `fmt.Sprintf("%s", "string")`
- `!fmtUint`: Show `%d` To Complate `fmt.Sprintf("%d", uint)`
- `!fmtFloat`: Show `%g` To Complate `fmt.Sprintf("%g", float)`
- `!switch`: Show `switch expression {`
  `case condition:`
  `}`
- `!filterMapString`: Show `data := map[string]string{`
  `"?.eq": "?string"`
  `}`
- `!split`: Show `"strings.Split(?, "?")"`
- `!findAll`: Show `Query Gorm FindAll Data`
- `!findByID`: Show `Query Gorm FindByID Data`
- `!create`: Show `Query Gorm Create Data`
- `!update`: Show `Query Gorm Update Data`
- `!delete`: Show `Query Gorm Delete Data`

And others

## Contribution

- Sure, I'd be happy to help! You can contribute to the development of this extension by adding new Go code snippets or improving existing ones. Please visit our GitHub repository at [repositori GitHub](https://github.com/takahashiumaru/go-snippets) for more information.

## Licence

- This extension is licensed under the [MIT License](https://opensource.org/licenses/MIT). Please refer to the LICENSE file for more information.

## Problem Report

- If you encounter any issues while using this project or have suggestions for improvement, please create a new issue in [issue baru](https://github.com/takahashiumaru/go-snippets). We will make every effort to address it as soon as possible.

## Support

- If you encounter any issues or have questions regarding this extension, please create a new issue in our GitHub repository [issue](https://github.com/takahashiumaru/go-snippets).

Thank you for using the VSCode extension for Go (Golang)!
