# Distress Frequencies

## Disclaimer

```
            /\              Depending on your location, transmitting or
           //\\             listening on some or all of these frequencies may
          //  \\            require a permit, license, or accreditation. Always
         //    \\           check your local regulations and act responsibly.
        //  ██  \\
       //   ██   \\         This information is for educational purposes only.
      //    ██    \\        Double-check every entry against reliable and
     //            \\       up-to-date official sources. It may not be accurate
    //      ██      \\      or applicable to your region. Use at your own risk
   //                \\     and in accordance with the law.
  //==================\\                                                 EA7RCT

         WARNING!
```

## Frequencies

| ! | Frequency     | Mode                   | Domain       | Alias   | Region         | Comment   |
| - | ------------- | ---------------------- | ------------ | ------- | -------------- | --------- |
| ! | 121.5 MHz     | AM                     | Aeronautical | IAD     | International  | International Air Distress |
|   | 243.0 MHz     | AM                     | Aeronautical | MAD     | International  | Military Air Distress |
|   | 2.182 MHz     | USB                    | Maritime     | HF2     | International  |           |
|   | 4.125 MHz     | USB                    | Maritime     | HF4     | International  |           |
|   | 6.215 MHz     | USB                    | Maritime     | HF6     | International  |           |
|   | 8.291 MHz     | USB                    | Maritime     | HF8     | International  |           |
|   | 12.290 MHz    | USB                    | Maritime     | HF12    | International  |           |
|   | 16.420 MHz    | USB                    | Maritime     | HF16    | International  |           |
| ! | 156.525 MHz   | Digital (DSC)          | Maritime     | CH70    | International  |           |
| ! | 156.800 MHz   | FM                     | Maritime     | CH16    | International  |           |
|   | 3.8025 MHz    | USB                    | Gov          |         | Spain          | Protección Civil 80m |
|   | 6.9915 MHz    | USB                    | Gov          |         | Spain          | Protección Civil 40m |
|   | 13.987 MHz    | USB                    | Gov          |         | Spain          | Protección Civil 20m |
| * | 146.175 MHz   | FM                     | Gov          | REMER   | Spain          | Red de Radio Emergencias del Ministerio del Interior + Protección Civil |
|   | 27.065 MHz    | AM (& FM?)             | Citizen band | CB-CH9  | International  | Not exlcusive, only recommended |
| * | 27.185 MHz    | AM & FM                | Citizen band | CB-CH19 | International  | Road and trucker channel |
|   | 446.00625 MHz | FM + CTCSS-12 (100 Hz) | PMR (Generic)| PMR1-12 | Spain          | 1-12 = 112 = Spanish emergency phone number |
|   | 446.08125 MHz | FM + CTCSS-7 (85.4 Hz) | PMR (Hiking) | PMR7-7  | Spain          |  |
|   | 3.760 MHz     | LSB                    | Amateur 80m  |         | International? | Not exclusive, only recommended |
|   | 7.110 MHz     | LSB                    | Amateur 40m  |         | International? | Not exclusive, only recommended |
|   | 14.300 MHz    | USB                    | Amateur 20m  |         | International? | Not exclusive, only recommended |
|   | 18.160 MHz    | USB                    | Amateur 17m  |         | International? | Not exclusive, only recommended |
|   | 21.360 MHz    | USB                    | Amateur 15m  |         | International? | Not exclusive, only recommended |
|   | 145.550 MHz   | FM                     | Amateur 2m   |         | International? | Not exclusive, only recommended |
|   | 433.550 MHz   | FM                     | Amateur 70cm |         | International? | Not exclusive, only recommended |


``` yaml
       !/*: Usually well-monitored (!) or active (*) frequencies.
 Frequency: Channel frequency or digital radio channel.
      Mode: Modulation, subtones, encoding, etc.
    Domain: Application domain or channel attribution.
     Alias: Common name of the frequency/channel.
    Region: Where the frequency is monitored.
   Comment: Any other relevant considerations.
```

## Recommendations

- Phone first: Before traveling, memorize the local emergency phone number for
  the areas you'll be in. Outside aviation or maritime environments, using your
  phone is usually the fastest and most reliable option if available.
- Location first, details later: When reporting an emergency, prioritize stating
  your location clearly before giving specific details. Rescue efforts depend on
  reaching your location quickly, even if communication breaks before you can
  state your exact emergency.
- If relying on 2m or 70cm Amateur Radio, research local repeaters beforehand.
  These are actively monitored but remember:
    - They often have different transmit and receive frequencies.
    - They may require a subtone for access.

## Contribute

Feel free to pull request new frequencies or correct any mistake you spot.

