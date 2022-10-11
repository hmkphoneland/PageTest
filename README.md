# Minimal c# code to load a FastReport report template, populate a dataset, then export to PDF file.

> Warning: FastReport is a commercial product with price starting at $499. 
> They also offer a [free open source][FROSgit] edition but the PDF export feature is actually an image export. That is, the text of the rendered PDF neither be selected nor copied.
> For the purpose of creating a proof-of-concept product, I opted to use their [trial edition][FRT] instead of their open source edition.

[FROSgit]:https://github.com/FastReports/FastReport
[FRT]:https://www.fast-report.com/en/download/fast-report-net

1. Open Visual Studio 2022 and create a console application.
2. Optional. Set the target OS to Windows. This will minimize the file dependencies of FastReport nuget.
3. Go to Package Manager Console and run the following:
`Install-Package FastReport.Net.Demo`
4. 