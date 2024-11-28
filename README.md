<h1 align="center">who am i?</h1>

```hs
module Main where

data Person = Person
  { name :: String
  , hobby :: [String]
  , status :: String
  , origin :: String
  , quote :: String
  , socialNetwork :: String
  }

fugoou :: Person
fugoou = Person
  { name = "Nicko Fajar"
  , hobby = ["Watching Anime", "Reading Manga", "Reading Novel"]
  , status = "Student"
  , origin = "Indonesia"
  , quote = "Nothing is easy, but nothing is impossible."
  , socialNetwork = "Connect with me on https://himote.xyz"
  }

main :: IO ()
main = do
  putStrLn $ "Hello, I'm " ++ name fugoou ++ "."
  putStrLn $ "I am a " ++ status fugoou ++ " from " ++ origin fugoou ++ "."
  putStrLn "My Hobbies include:"
  mapM_ putStrLn $ map (\h -> "- " ++ h) (hobby fugoou)
  putStrLn $ "One of my favorite quotes: \"" ++ quote fugoou ++ "\""
  putStrLn $ "Let's connect on my social network: " ++ socialNetwork fugoou
```

<p align="center">
  <a href="https://open.spotify.com/user/31jq7g4rf7d3u6guzx5uqzor5qrq?si=aUS6tB5iSpmNcOq2kkJDGA" target="_blank"><img src="https://now-playing-on-spotify.vercel.app/api/spotify" alt="Spotify Now Playing" width="350"/></a>
</p>

<div align="center">
  <img align="center" alt="count" src="https://count.getloli.com/get/@:fugoou?theme=booru-lewd">
</div>

<p align="center">
	<img width="625em" src="./github-metrics.svg" />
