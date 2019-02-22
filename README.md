# VimeoExtractor

Vimeo Url Extractor Download Videos
Android based Vimeo url extractor
=======================================================

These are the urls to the Vimeo Video file, so you can stream or download them.

* Builds: [![JitPack](https://jitpack.io/v/Ashusolanki/VimeoExtractor.svg)](https://jitpack.io/#Ashusolanki/VimeoExtractor)

## Gradle

To always build from the latest commit with all updates. Add the JitPack repository:

```java
repositories {
    maven { url "https://jitpack.io" }
}
```

And the dependency:

```
dependencies 
 {
    implementation 'com.github.Ashusolanki:TwitterUrlExtractor:0.0.1'
 }
```  

## Usage

#VimeoExtractor
```

        new VimeoExtractor()
        {
            @Override
            protected void onExtractionComplete(ArrayList<VimeoFile> vimeoFileArrayList) 
            {
              //complete
            }
            @Override
            protected void onExtractionFail(String Error) 
            {
              /fail
            }
        }.Extractor(this.getActivity(), videoURL);
        
```

#VimeoFile
```
    getQuality();
    getUrl();
    getExt();
    getFilename();
    getAuthor();
    getSize();
    getDuration();

```


