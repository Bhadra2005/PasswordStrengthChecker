
# Password Strength Checker

The website is used to check the strength of a password. It counts total number of characters, uppercase and lowercase letters, numbers and special characters. It generates passwords with 12 characters for those who have difficulty in making a strong one. It displays random quotes each time a new password is generated. The website asks permission to access the device location to display the current temperature and weather condition of my location.
## Authors

- [@BhadraR](https://www.github.com/Bhadra2005)
- [@JesseTeresaBiju](https://www.github.com/jesteresabiju)
- [@AryaPradeep](https://www.github.com/aryapradeep147)
- [@AshwiniNK](https://www.github.com/123MGHVH)


## API Reference

#### Get all items

```http
  fetch('http://api.weatherapi.com/v1/current.json?key=2f4b682647214cb08c2213623240603&q=${latitude},${longitude}')
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | 2f4b682647214cb08c2213623240603 |

#### Get item

```http
  fetch('https://api.quotable.io/random')

```

## Screenshots

![App Screenshot](1.jpg)
![App Screenshot](2.jpg)
