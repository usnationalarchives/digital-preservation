# Preservation Action Plan for Digital Audio
### National Archives and Records Administration (NARA)

Plan Date: 202411
Template: 202105

#### Digital Audio
The Digital Audio category encompasses formats used to encode recorded sound as machine readable files by converting acoustic sound waves into digital signals. Digital audio formats are generally composed of both an encoding/decoding method (codec) and a container/wrapper format which encapsulates the bitstreams and includes other associated data such as metadata. The file extension typically denotes the container/wrapper format.  

Digital audio is defined as an audio waveform that has been created as, or converted into, digital form and encoded as a sequence of numerical samples with the purpose of converting to a continuous analog signal reproducing sound. The source of the captured audio information may be a direct digital capture of acoustic sound waves, a digital capture of an analog recording, a copy of a previous digital encoding, or a transcoding from a previous digital encoding.

#### Significant Properties of Digital Audio
To render an authentic digital audio file one must preserve the structural and technical metadata that allows for proper transmission of the audio signal (duration, channels, channel mapping, sampling rate, and bit depth). Resolution is a function of the bandwidth and flat equalization of analog circuitry before A/D conversion, sample bit depth, sample rate, and compression when lossy compression is used.See NARA’s Internal Products and Services “[Glossary of Useful Terms](https://www.archives.gov/preservation/products/definitions/terms-glossary "Glossary of Useful Terms").”

General requirements for digital audio records: Digitize to standards appropriate for the accurate preservation of the original audio when converting analog material (e.g., audio cassettes, grooved media, and magnetic audio tapes, etc.). When transcoding from a digital original (born digital) to a file (e.g., Compact Disk, DAT, or from a different digital file format, etc.), strive to keep the same sampling attributes as the digital original (i.e., sample bit depth and frequency), and the same sound field and compression schemes if appropriate for the new preservation file format. Transfer digital audio at a minimum of 16 bits per sample, but 24 bits per sample is encouraged; and transfer digital audio at a minimum sample rate of at least 44.1 KHz, but sampling at 96 KHz is encouraged.


#### Appearance
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
| File size  | Determined by bit depth, sampling rate, number of channels, compression, duration, and ancillary data such as metadata. | |

#### Structure
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
| Layout Structure  | Embedded technical metadata describing, among other things: format, interleaved channels, samples per second, data rate, data block size, bits per sample, and GUID. | |
| Audio Channel  | A single stream of recorded sound. | Multiple channels can exist in one audio file. Most common configurations are mono, 2.0 (stereo - left and right), 3.1 (home set up) 5.1 (surround sound), and 7.1 (fuller surround sound). |


#### Behavior
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
|Display | Waveform | Audio signal is visually represented as a waveform, or data elements that characterize a sound. Amplitude is displayed on the Y axis, the X axis is time. Visual peaks should stay within the limits of the digital recording range and not go above 0dB.  |
|Rendering| The process of generating one file to include all audio components.|Rendering can lead to compression: factors include the decibel threshold, decibel ratio, encoding/converting to a lossy codec, etc. |


#### Context
| Name  | Definition  | Function Description  |
| ------------ | ------------ | ------------ |
| Metadata | May include administrative, descriptive, and/or technical metadata. |  Metadata can be embedded or saved as a sidecar file. Examples of metadata fields include coding history, origination date, title, creator, collection, unique identifier, etc.  |


#### Current NARA Transfer Guidance for Structured Digital Audio
[Bulletin 2014-04](https://www.archives.gov/records-mgmt/bulletins/2014/2014-04.html "Bulletin 2014-04")

- Preferred:  
	- Broadcast Wave (BWF) with LPCM Audio
	- Free Lossless Audio Codec (FLAC)

- Acceptable: 
	- Audio Interchange Format (AIFF) with LPCM Audio
	- MPEG Audio Layer III (MP3) with MP3 or Lame Audio
	- Wave Waveform Audio File Format (Wave, WAV) with LPCM Audio



#### Current NARA Format(s) for Public Access and Reference for Digital Audio
Formats for Public Access are those made available online through the National Archives Catalog. Formats for Reference are defined as those made available to researchers upon direct requests for digital copies.

Formats Available for Public Access: MP3, WAV. Other file formats may be present depending on when they were added to the Catalog. 

Format(s) Available for Reference: MPEG-1 Audio Layer III (MP3)


#### Current NARA Internal Products and Services for Digital Audio

NARA creates a wide variety of audio, video and motion picture products from NARA records in response to reference requests as well as for planned preservation projects and internal staff use. These specifications and standards are written for use by NARA’s Moving Image and Sound Preservation Labs. They do not necessarily reflect all industry preservation standards, and are not intended as universal guidance or recommendations.
- [NARA Internal Products and Services](https://www.archives.gov/preservation/products "NARA Internal Products and Services")
- [Additional Audio Guidance](https://www.archives.gov/preservation/formats/audio-toc.html "Audio Guidance")
