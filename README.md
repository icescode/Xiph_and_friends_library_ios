This is pre compiled Xiph and friends static library (bitcode enabled) for iOS (armv7 and arm64) arch. 

1. libogg.a
2. libvorbis.a
3. libtheora.a
4. libvorbisenc.a
5. libmp3lame.a
6. libshout.a (MP3, OGG and AAC)
7. libfaac.a <non free>
8. libopus.a
9. libflac.a
10. libshout_with_opus.a (MP3, OGG and Opus)

if you want to use libshout API on iOS then put all header (shout,vorbis,ogg,theora) files to your project, and linked with libshout (use shout.h) or libshout_with_opus.a (rename shout_with_opus > shout.h) , libogg, libvorbis, libtheora and libvorbisenc.

libmp3lame, libopus, libflac are optional.

all headers files are in header folder.

