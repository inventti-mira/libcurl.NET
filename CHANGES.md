# libcurl.NET Change Log

## Version 1.4.1 - February 18, 2016
- Fixed a few x64-related bugs/crashes
- Created x86 and x64 Nuget packages

## Version 1.4 - February 16, 2016
- Updated libcurl from 7.13.0 to 7.40.0
- Added x64 configuration

## Version 1.3 - February 17, 2005
- Initial public release of the source code on sourceforge.net. 
- Updated API to reflect curl 7.13.0

## Version 1.2.1 - December 8, 2004
- Fixed Slist.Append()

## Version 1.2 - December 1, 2004
- Fixed Share callbacks to properly reference GCHandle
- Rearranged share and easy cleanup sequences
- Multi.Select() uses m_maxFD + 1
- Fixed Easy.GetInfo for the DateTime object case!
- Fixed Easy.GetInfo to use concrete types for the output parameter
