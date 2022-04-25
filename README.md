# DependencyTrack
Get vulnerable log4j app from following link -> https://github.com/justincormack/log4jpoc
Run following command with syft --> syft packages justinjustin/poc -o cyclonedx > sbomlog4j.xml
Upload sbom file into dependencyTrack and refresh the page
Make sure you enabled OSSIndex so that all vulnerabilities will be detected
Check for audit vulnerabilities
