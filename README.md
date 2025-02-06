# go-templates-snippets

This extension contains code snippets for Golang templates for Visual Studio Code editor. Supports `.go`, `.gotmpl`, `.html` and their file associations.

## Supported file extensions
* `.go`
* `.gotmpl`
* `.html`
* file associations of `.gotmpl` and `.html`

## Snippets

Below is a list of all available snippets.

| Trigger               | Content |
| -------:              | ------- |
| `tblock`              | `{{ block "name" pipeline }}`
| `tblockend`           | `{{ block "name" pipeline }} ... {{ end }}` 
| `tbreak`              | `{{ break }}` 
| `tcontinue`           | `{{ continue }}` 
| `tdefine`             | `{{ define "name" }}` 
| `tdefineend`          | `{{ define "name" }} ... {{ end }}` 
| `telse`               | `{{ else }}` 
| `telseif`             | `{{ else if (condition) }}` 
| `tend`                | `{{ end }}` 
| `tif`                 | `{{ if (condition) }}`
| `tifend`              | `{{ if (condition) }} ... {{ end }}`
| `tifelseend`          | `{{ if (condition) }} ... {{ else }} ... {{ end }}` 
| `tpartial`            | `{{ partial "name" }}`
| `tpipeline`           | `{{ pipeline }}`
| `trange`              | `{{ range pipeline }}`
| `trangeend`           | `{{ range pipeline }} ... {{ end }}`
| `ttemplate`           | `{{ template "name" pipeline }}` 
| `twith`               | `{{ with pipeline }}`
| `twithend`            | `{{ with pipeline }} ... {{ end }}`
| `twithelseend`        | `{{ with pipeline }} ... {{ else }} ... {{ end }}` 
| `twithelsepipeeend`   | `{{ with pipeline }} ... {{ else with pipeline }} ... {{ end }}`

### Within a template file

<video src='./assets/videos/golang-templates-snippets-markup.mp4' width=600 controls></video>

### Within a Go file
Press <kbd>Space</kbd> to generate suggestions

<video src='./assets/videos/golang-templates-snippets-go.mp4' width=600 controls></video>

<!-- ## Release Notes

Users appreciate release notes as you update your extension.

### 1.0.0

Initial release of ...

### 1.0.1

Fixed issue #.

### 1.1.0

Added features X, Y, and Z.

--- -->

Kindly leave a star ⭐ if you find this project useful. It is a source of encouragement to me 🙏.

Cheers!

<a target="_blank" href="https://icons8.com/icon/44442/golang">Golang</a> icon by <a target="_blank" href="https://icons8.com">Icons8</a>
