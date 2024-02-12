# GET-Current-Location-Implement


free location site
site: https://nominatim.openstreetmap.org/reverse?format=json&lat=21.2238336&lon=72.8367104


//use this code
react js code implementation
useEffect(() => {
navigator.geolocation.getCurrentPosition((response) => {
    console.log('===>>> response', response)
})
})
