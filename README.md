# BlackHat Arsenal 2017 Demo Assets

## Slides and KML files

### Notes

* Slides are in the file named SITCH_BlackHat_Arsenal_2017-SLIDES.pdf
* `napa.kml` and `vegas.kml`
  * Open with Google Earth
  * `napa.kml`:
    * First run testing "solo mode"
    * Geo resolution needed improvement (fewer geo samples, clustering of alerts)
    * The southernmost alert: `MCC 001 should not be observed by this sensor.`
  * `vegas.kml`
    * Started on the way out of San Francisco, en route to Las Vegas.
    * Alerting ends near Mono Lake, where sensors were switched off for the night.
    * Attempted to re-activate SITCH from Coyote Flat, above Bishop, a few days later.
    * Alerts were generated when re-entering Bishop, and through the desert to Las Vegas, but GPS was unable to acquire a fix.  
      * Possible GPS issues stemming from operation in the desert heat.
      * These alerts (Bishop to Las Vegas) were all located at (0,0), so were not included in KML.
