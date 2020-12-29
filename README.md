# basic-turkic-wordlist
A basic Turkic word list in IPA for testing computational historical linguistics algorithms

## Limitations
* There's only one word given per sense
  * Sometimes the choice is arbitrary and forced as to which word is chosen
  * Often this approach hides the existence of cognates
* Sometimes cognates are favoured because of how the dictionary was built.
* Some data is probably not perfect, for a variety of reasons:
  * Differences in sources
  * Inconsistency with translations, e.g. where a language has more than one word for a particular item (which is "default"?)
    * Problematic words are "dog" (kœpek/ijt), "breast" (kœkys/kœkyrek/tœʃ), "sun" (kyn/kyneʃ/quyaʃ)
  * Lack of actual knowledge by the contributor(s) of some of the languages
  * Phonemicky versus phoneticky transcriptions
    * Subphonemic voicing (or other lenition) was not indicated in Chuvash
    * Initial rounding of /ɑ/ (as [ɒ]) was indicated in Tatar
  
Please feel free to suggest ways to improve upon any of these (through the issue tracker), or submit fixes (via a pull request).

Requests for adding individual words will also be considered (through the issue tracker).

## Sources
* Much of the basic wordlist was built from [StarLing's Turkic etymological database](http://starling.rinet.ru/cgi-bin/query.cgi?basename=\data\alt\turcet&root=config&morpho=0)
  * This has the occasional effect of favouring cognates
  * Transcriptions were adjusted based on JNW's [rudimentary] familiarity with some languages and to be more IPA-compatible
* The Kazakh and Kyrgyz data was drawn on JNW's own [L2/linguist] knowledge of the languages, and checked against dictionaries
* Other sources were consulted to clean up and expand coverage of individual languages.  These sources include:
  * Imart on Fu-yü Gyrgys
  * Clark (1998).  Turkmen Reference Grammar.
  * Баскаков et al. (1968).  Түкменче-русча сөзлүк.  [for Turkmen]
  * Рассадин, В.И. (1995).  Тофаларско-русский / русско-тофаларский словарь.  [for Tofa]
  * [seslisozluk.com](http://seslisozluk.com) for Turkish.
  * [tyvan.ru](http://tyvan.ru) for Tuvan.
  * [samah.chv.su](http://samah.chv.su/cgi-bin/s.cgi) for Chuvash.
  * [sakhatyla.ru](http://sakhatyla.ru) for Sakha.
  * [CTILD](http://www.indiana.edu/~ctild/dict/) for Uzbek.
  * Чумакаев et al. (2015).  Русско-алтайский словарь / орус-алтай сӧзлик.  [for Altay]
  * Гаркавец, А.Н. & Усеинв, С.М. (2002).  Крымскотатарско-русско-украинский словарь.  [for Crimean Tatar]
  * Бутанаев, В.Я. (2011).  Русско-хакасский словарь.  [for Khakas] 
  * Астемирова, Ф.Б. & Н.Э. Гаджиахмедов (2008).  Школьный руссокумыкский словарь / школалар учун орусча-къумукъча сёзлюк.  [for Kumyk]
  * Hahn, Reinhard (1991).  An Annotated Sample of Ili Turki.
  * Xiāngrú, Zhào & Reinhard Hahn (1989).  The Ili Turk People and Their Language
  * Гаркавець, Олександр (2000).  Урумський словник.  [for Urum]

## Citing

This data is dual licensed under GPL v3.0 and CC-BY-SA 4.0.  If you use the data for a project and publish the results, please [cite the repository](https://academia.stackexchange.com/a/14015), listing all the contributors as authors.  The full list of contributors currently consists of:
* Jonathan North Washington
