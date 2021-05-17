
# Nuclei Templates

```
Nuclei is a fast tool for configurable targeted scanning 
based on templates offering massive extensibility and ease of use.

Usage:
  nuclei [flags]

Flags:
   -H, -header value                      Custom Header.
   -biid, -burp-collaborator-biid string  Burp Collaborator BIID
   -bs, -bulk-size int                    Maximum Number of hosts analyzed in parallel per template (default 25)
   -c, -concurrency int                   Maximum Number of templates executed in parallel (default 10)
   -config string                         Nuclei configuration file
   -de, -disk-export string               Directory on disk to export reports in markdown to
   -debug                                 Debugging request and responses
   -debug-req                             Debugging request
   -debug-resp                            Debugging response
   -et, -exclude value                    Templates to exclude, supports single and multiple templates using directory.
   -etags, -exclude-tags value            Exclude templates with the provided tags
   -headless                              Enable headless browser based templates support
   -impact, -severity value               Templates to run based on severity, supports single and multiple severity.
   -irr, -include-rr                      Write requests/responses for matches in JSON output
   -interactions-cache-size int           Number of requests to keep in interactions cache (default 5000)
   -interactions-cooldown-period int      Extra time for interaction polling before exiting (default 5)
   -interactions-eviction int             Number of seconds to wait before evicting requests from cache (default 60)
   -interactions-poll-duration int        Number of seconds before each interaction poll request (default 5)
   -interactsh-url string                 Interactsh Server URL (default https://interact.sh)
   -json                                  Write json output to files
   -l, -list string                       List of URLs to run templates on
   -metrics                               Expose nuclei metrics on a port
   -metrics-port int                      Port to expose nuclei metrics on (default 9092)
   -nc, -no-color                         Disable colors in output
   -nt, -new-templates                    Only run newly added templates
   -nm, -no-meta                          Don't display metadata for the matches
   -no-interactsh                         Do not use interactsh server for blind interaction polling
   -o, -output string                     File to write output to (optional)
   -page-timeout int                      Seconds to wait for each page in headless (default 20)
   -passive                               Enable Passive HTTP response processing mode
   -project                               Use a project folder to avoid sending same request multiple times
   -project-path string                   Use a user defined project folder, temporary folder is used if not specified but enabled
   -proxy-socks-url string                URL of the proxy socks server
   -proxy-url string                      URL of the proxy server
   -r, -resolvers string                  File containing resolver list for nuclei
   -rl, -rate-limit int                   Maximum requests to send per second (default 150)
   -rc, -report-config string             Nuclei Reporting Module configuration file
   -rdb, -report-db string                Local Nuclei Reporting Database (Always use this to persistent report data)
   -retries int                           Number of times to retry a failed request (default 1)
   -show-browser                          Show the browser on the screen
   -si, -stats-interval int               Number of seconds between each stats line (default 5)
   -silent                                Show only results in output
   -spm, -stop-at-first-path              Stop processing http requests at first match (this may break template/workflow logic)
   -stats                                 Display stats of the running scan
   -system-resolvers                      Use system dns resolving as error fallback
   -t, -templates value                   Templates to run, supports single and multiple templates using directory.
   -tags value                            Tags to execute templates for
   -u, -target string                     URL to scan with nuclei
   -tv, -templates-version                Shows the installed nuclei-templates version
   -timeout int                           Time to wait in seconds before timeout (default 5)
   -tl                                    List available templates
   -trace-log string                      File to write sent requests trace log
   -ud, -update-directory string          Directory storing nuclei-templates (default /root/nuclei-templates)
   -ut, -update-templates                 Download / updates nuclei community templates
   -v, -verbose                           Show verbose output
   -version                               Show version of nuclei
   -w, -workflows value                   Workflows to run for nuclei
   ```
