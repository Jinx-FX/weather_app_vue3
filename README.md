# weather_app_vue3

Built with [vue3](https://vuejs.org/guide/introduction.html), [vite](https://github.com/vitejs/vite) and [tailwind css](https://tailwindcss.com/) 

# Component Structure

- App
  - HomeView
    - CityList
      - CityCard
    - CityCardSkeleton
      - AnimatedPlaceholder
    - CityView
      - AsyncCityView
      - CityViewSkeleton
        - AnimatedPlaceholder
  - SiteNavigaion
    - BaseModal

# API

- [openweathermap](https://openweathermap.org/api)
- [mapbox](https://api.mapbox.com/geocoding/v5/mapbox.places/)

# reference

- [net_ninja_vue_3_weather_app](https://github.com/johnkomarnicki/net_ninja_vue_3_weather_app)

# Improve

- Temperature unit: F => C
- Make sure that added cities are not displayed `+` when reloading 
- `remove` button will also be displayed in cities not added

