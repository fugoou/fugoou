<h1 align="center">who am i?</h1>

```hs
module Main where

data Person = Person
  { name :: String
  , hobby :: [String]
  , status :: String
  , origin :: String
  , quote :: String
  , website :: String
  }

fugoou :: Person
fugoou = Person
  { name = "Nicko Fajar"
  , hobby = ["Watching Anime", "Reading Manga", "Reading Novel"]
  , status = "Student"
  , origin = "Indonesia"
  , quote = "Nothing is easy, but nothing is impossible."
  , website = "https://n4x.top"
  }

main :: IO ()
main = do
  putStrLn $ "Hello, I'm " ++ name fugoou ++ "."
  putStrLn $ "I am a " ++ status fugoou ++ " from " ++ origin fugoou ++ "."
  putStrLn "My Hobbies include:"
  mapM_ putStrLn $ map (\h -> "- " ++ h) (hobby fugoou)
  putStrLn $ "One of my favorite quotes: \"" ++ quote fugoou ++ "\""
  putStrLn $ "Visit my website: " ++ website fugoou
```

<div align="center">
	<img align="center" alt="count" src="https://count.getloli.com/get/@:fugoou?theme=booru-lewd">
	<img width="625em" src="./github-metrics.svg" />
</div>
