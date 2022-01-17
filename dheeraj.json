const express = require('express')
const app = express()
const port = 3000

app.get('/data/2.5/weather', (req, res) => {
    res.json({ "coord": { "lon": -123.262, "lat": 44.5646 }, "weather": [{ "id": 701, "main": "Mist", "description": "mist", "icon": "50n" }], "base": "stations", "main": { "temp": 276.61, "feels_like": 275.29, "temp_min": 275.36, "temp_max": 279.95, "pressure": 1019, "humidity": 80 }, "visibility": 6437, "wind": { "speed": 1.54, "deg": 140 }, "clouds": { "all": 100 }, "dt": 1642392459, "sys": { "type": 2, "id": 2040223, "country": "US", "sunrise": 1642347934, "sunset": 1642381185 }, "timezone": -28800, "id": 5720727, "name": "Corvallis", "cod": 200 })
})

app.listen(port, () => {
    console.log(`Example app listening at http://localhost:${port}`)
})
