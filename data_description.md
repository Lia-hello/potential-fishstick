Data source：
https://huggingface.co/datasets/ailsntua/Chordonomicon/tree/main?utm_source
https://huggingface.co/datasets/ailsntua/Chordonomicon?utm_source
https://huggingface.co/search/full-text
https://github.com/
Collection method：
 csv from hugging face public repository
Collection date and time period covered：
2000-2026
Number of observations (rows) and variables (columns)：
2（before and after 2023）x 7 （artists，year，song，chord，clean_chord)
Variable descriptions: for each column, provide the variable name, data type,description, and an example value：
Variable Name	Data Type	Description	Example Value
artists	string	Name of the music artist(s)	Taylor Swift
year	integer	Release year of the song; used to split before 2023 and after 2023	2022
song	string	Full title of the song	Cruel Summer
chord	string	Raw chord progression extracted from the song	C G Am F
clean_chord	string	Standardized & cleaned chord notation (no symbols, consistent format)	C G Am F
Any known data quality issues (missing values, duplicates, encoding issues)

