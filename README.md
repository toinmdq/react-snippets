# react-snippets

_You can find all the **snippets** into snippets folder_

## HOOKS

- useState
- useState
- useTheme
- useAppSelector
- useNavigate
- useAppDispatch
- useIsMounted
- useHistory
- useEffect
- useForm
- useDialog
- useDialogOptions

E.g.:

```json
{
  "useState": {
    "prefix": "useState",
    "body": [
      "const [ ${1:first}, set${1/(.*)/${1:/capitalize}/} ] = useState(${0:initialState});"
    ]
  }
}
```

## NEXT

- nextPage
-

E.g.:

```json
{
  "new Next Page": {
    "prefix": "nextPage",
    "body": [
      "\t\t",
      "export default function ${TM_DIRECTORY/.*\\/(.)(.+)$/${1:/upcase}$2/}() {",
      "\t\t",
      "\treturn (",
      "\t\t<>",
      "\t\t\t$0",
      "\t\t</>",
      "\t);",
      "};",
      ""
    ]
  }
}
```

## REACT COMPONENTS

- rafc mui
- rafc mui screen

E.g.:

```json
{
  "rafc": {
    "prefix": "rafc",
    "body": [
      "",
      "export const ${TM_FILENAME_BASE} = (): JSX.Element => {",
      "\t\t",
      "\treturn (",
      "\t\t<>",
      "\t\t\t$0",
      "\t\t</>",
      "\t);",
      "};"
    ]
  }
}
```

## OTHERS

- TODO
- FIX

E.g.:

```json
{
  "TODO fast": {
    "prefix": "todo",
    "body": ["// TODO: $1"]
  },

  "FIX fast": {
    "prefix": "fix",
    "body": ["// FIXME: $1"]
  }
}
```
