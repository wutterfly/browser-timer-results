# Gesammelte Ergebnisse
Ergebnisse aus den Apps [browser-timer](https://github.com/wutterfly/browser-timer) und [browser-timer-rs](https://github.com/wutterfly/browser-timer-rs). 

Zwischenergebnisse sind nicht enthalten.


# Datensätze

## Browser-OS Unterschied
Ein Vergleich zwischen gleichzeitig gesammelten Input-Events im Browser und nativer Anwendung (Rust).
- braucht ca. 5 bis 10 min pro Datensatz

#### Chrome

- [x] natürlicher Nutzer [Datei](./browser/chrome/complete.csv)
- [x] maschineller Nutzer [Datei](./browser/chrome/complete.csv)
- [x] natürlicher Nutzer (Key Up and Down) [Datei](./browser_extended/chrome/complete.csv)
- [x] maschineller Nutzer (Key Up and Down) [Datei](./browser_extended/chrome/complete.csv)

#### Chromium
- [x] natürlicher Nutzer [Datei](./browser/chromium/complete.csv)
- [x] maschineller Nutzer [Datei](./browser/chromium/complete.csv)
- [x] natürlicher Nutzer (Key Up and Down) [Datei](./browser_extended/chromium/complete.csv)
- [x] maschineller Nutzer (Key Up and Down) [Datei](./browser_extended/chromium/complete.csv)

#### Edge

- [x] natürlicher Nutzer [Datei](./browser/edge/complete.csv)
- [x] maschineller Nutzer [Datei](./browser/edge/complete.csv)
- [x] natürlicher Nutzer (Key Up and Down) [Datei](./browser_extended/edge/complete.csv)
- [x] maschineller Nutzer (Key Up and Down) [Datei](./browser_extended/edge/complete.csv)

#### Firefox

- [x] natürlicher Nutzer [Datei](./browser/firefox/complete.csv)
- [x] maschineller Nutzer [Datei](./browser/firefox/complete.csv)
- [x] natürlicher Nutzer (Key Up and Down) [Datei](./browser_extended/firefox/complete.csv)
- [x] maschineller Nutzer (Key Up and Down) [Datei](./browser_extended/firefox/complete.csv)

#### Tor

- [x] natürlicher Nutzer [Datei](./browser/tor/complete.csv)
- [x] maschineller Nutzer [Datei](./browser/tor/complete.csv)
- [x] natürlicher Nutzer (Key Up and Down) [Datei](./browser_extended/tor/complete.csv)
- [x] maschineller Nutzer (Key Up and Down) [Datei](./browser_extended/tor/complete.csv)

#### Safari

- [x] natürlicher Nutzer [Datei](./browser/safari/complete.csv)
- [x] maschineller Nutzer [Datei](./browser/safari/complete.csv)
- [ ] natürlicher Nutzer (Key Up and Down) [Datei](./browser_extended/safari/complete.csv)
- [ ] maschineller Nutzer (Key Up and Down) [Datei](./browser_extended/safari/complete.csv)



## Zeitstempelproben in Browser

Eine Reihe von Input-Events werden im Browser simuliert und zugehörige Zeitstempel gesammelt.
- braucht ca. 5 bis 10 min pro Datensatz


#### Chrome [Datei](./timer/chrome/complete.csv)

- [x] isoliert
- [x] isoliert async (loading a lot of different webpages in the background)
- [x] isoliert graphics (executing graphics application in the background)
- [x] isoliert video5 (playing 5 hight-definition videos in the backgound)
- [x] unisoliert
- [x] unisoliert async (loading a lot of different webpages in the background)
- [x] unisoliert graphics (executing graphics application in the background)
- [x] unisoliert video5 (playing 5 hight-definition videos in the backgound)

#### Chromium [Datei](./timer/chromium/complete.csv)

- [x] isoliert
- [x] isoliert async (loading a lot of different webpages in the background)
- [x] isoliert graphics (executing graphics application in the background)
- [x] isoliert video5 (playing 5 hight-definition videos in the backgound)
- [x] unisoliert
- [x] unisoliert async (loading a lot of different webpages in the background)
- [x] unisoliert graphics (executing graphics application in the background)
- [x] unisoliert video5 (playing 5 hight-definition videos in the backgound)

#### Edge [Datei](./timer/edge/complete.csv)

- [x] isoliert
- [x] isoliert async (loading a lot of different webpages in the background)
- [x] isoliert graphics (executing graphics application in the background)
- [x] isoliert video5 (playing 5 hight-definition videos in the backgound)
- [x] unisoliert
- [x] unisoliert async (loading a lot of different webpages in the background)
- [x] unisoliert graphics (executing graphics application in the background)
- [x] unisoliert video5 (playing 5 hight-definition videos in the backgound)

#### Firefox [Datei](./timer/firefox/complete.csv)

- [x] isoliert
- [x] isoliert async (loading a lot of different webpages in the background)
- [x] isoliert graphics (executing graphics application in the background)
- [x] isoliert video5 (playing 5 hight-definition videos in the backgound)
- [x] unisoliert
- [x] unisoliert async (loading a lot of different webpages in the background)
- [x] unisoliert graphics (executing graphics application in the background)
- [x] unisoliert video5 (playing 5 hight-definition videos in the backgound)

#### Safari [Datei](./timer/safari/complete.csv)

- [x] isoliert
- [x] isoliert async (loading a lot of different webpages in the background)
- [x] isoliert graphics (executing graphics application in the background)
- [x] isoliert video5 (playing 5 hight-definition videos in the backgound)
- [x] unisoliert
- [x] unisoliert async (loading a lot of different webpages in the background)
- [x] unisoliert graphics (executing graphics application in the background)
- [x] unisoliert video5 (playing 5 hight-definition videos in the backgound)

#### Tor [Datei](./timer/safari/complete.csv)

- [x] unisoliert
- [x] unisoliert async (loading a lot of different webpages in the background)
- [x] unisoliert graphics (executing graphics application in the background)
- [x] unisoliert video5 (playing 5 hight-definition videos in the backgound)



## Passoword Simulation
- braucht 21 bis 22 Stunden

#### Chrome 
- [x] isoliert [Datei](./password/chrome/password_data_chrome_isolated/full_data_set.csv)
- [x] unisoliert [Datei](./password/chrome/password_data_chrome_unisolated/full_data_set.csv)
- [ ] isoliert (warm up) [Datei](./password/chrome/password_data_chrome_isolated_warmup/full_data_set.csv)
- [ ] unisoliert (warm up) [Datei](./password/chrome/password_data_chrome_unisolated_warmup/full_data_set.csv)

#### Chromium
- [x] isoliert [Datei](./password/chromium/password_data_chromium_isolated/full_data_set.csv)
- [x] unisoliert [Datei](./password/chromium/password_data_chromium_unisolated/full_data_set.csv)
- [ ] isoliert (warm up) [Datei](./password/chromium/password_data_chromium_isolated_warmup/full_data_set.csv)
- [ ] unisoliert (warm up) [Datei](./password/chromium/password_data_chromium_unisolated_warmup/full_data_set.csv)

#### Edge
- [x] isoliert [Datei](./password/edge/password_data_edge_isolated/full_data_set.csv)
- [x] unisoliert [Datei](./password/edge/password_data_edge_unisolated/full_data_set.csv)
- [ ] isoliert (warm up) [Datei](./password/edge/password_data_edge_isolated_warmup/full_data_set.csv)
- [ ] unisoliert (warm up) [Datei](./password/edge/password_data_edge_unisolated_warmup/full_data_set.csv)

#### Firefox
- [x] isoliert [Datei](./password/firefox/password_data_firefox_isolated/full_data_set.csv)
- [x] unisoliert [Datei](./password/firefox/password_data_firefox_unisolated/full_data_set.csv)
- [ ] isoliert (warm up) [Datei](./password/firefox/password_data_firefox_isolated_warmup/comfull_data_setplete.csv)
- [ ] unisoliert (warm up) [Datei](./password/firefox/password_data_firefox_unisolated_warmup/full_data_set.csv)

#### Firefox ResistFingerprinting (RF)
- [ ] isoliert (warm up) [Datei](./password/firefox_resistFingerprinting/firefox_isolated_resistFingerprinting_true/full_data_set)
- [x] unisoliert (warm up) [Datei](./password/firefox_resistFingerprinting/firefox_unisolated_resistFingerprinting_true/full_data_set.csv)

#### Tor
- [x] unisoliert [Datei](./password/tor/password_data_tor_unisolated/full_data_set.csv)
- [ ] unisoliert (warm up) [Datei](./password/tor/password_data_tor_unisolated_warmup/full_data_set.csv)

#### Safari
- [x] isoliert [Datei](./password/safari/password_data_safari_isolated/full_data_set.csv)
- [x] unisoliert [Datei](./password/safari/password_data_safari_unisolated/full_data_set.csv)
- [x] isoliert  (warm up) [Datei](./password/safari/password_data_safari_isolated_warm_up/full_data_set.csv)
- [x] unisoliert (warm up) [Datei](./password/safari/password_data_safari_unisolated_warm_up/full_data_set.csv)


## Frei-Text
- braucht bis zu 14 Stunden

#### Chrome
- [ ] isoliert [Datei](./freetext/chrome/)
- [ ] unisoliert [Datei](./freetext/chrome/)

#### Chromium
- [ ] isoliert [Datei](./freetext/chromium/)
- [ ] unisoliert [Datei](./freetext/chromium/)

#### Edge
- [ ] isoliert [Datei](./freetext/edge/)
- [ ] unisoliert [Datei](./freetext/edge/)

#### Firefox
- [ ] isoliert [Datei](./freetext/firefox/)
- [ ] unisoliert [Datei](./freetext/firefox/)

#### Firefox ResistFingerprinting (RF)
- [ ] isoliert [Datei](./freetext/firefox/)
- [ ] unisoliert [Datei](./freetext/firefox/)

#### Tor
- [ ] isoliert [Datei](./freetext/tor/)
- [ ] unisoliert [Datei](./freetext/tor/)

#### Safari
- [ ] isoliert [Datei](./freetext/safari/)
- [ ] unisoliert [Datei](./freetext/safari/)