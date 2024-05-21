## in package.json script section

### for linux/macos use :
`"copy:assets": "cp -r public/* dist/public",`

### for windows use :
`"copy:assets": "for %f in (public\\*) do xcopy \"%f\" dist\\public\\ /i /y",`
