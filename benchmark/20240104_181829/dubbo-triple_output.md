# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.447 ops/ms
# Warmup Iteration   2: 11.956 ops/ms
# Warmup Iteration   3: 12.605 ops/ms
Iteration   1: 12.615 ops/ms
Iteration   2: 12.989 ops/ms
Iteration   3: 12.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.843 ±(99.9%) 3.655 ops/ms [Average]
  (min, avg, max) = (12.615, 12.843, 12.989), stdev = 0.200
  CI (99.9%): [9.188, 16.498] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.813 ops/ms
# Warmup Iteration   2: 12.906 ops/ms
# Warmup Iteration   3: 13.065 ops/ms
Iteration   1: 12.978 ops/ms
Iteration   2: 12.844 ops/ms
Iteration   3: 13.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.946 ±(99.9%) 1.652 ops/ms [Average]
  (min, avg, max) = (12.844, 12.946, 13.016), stdev = 0.091
  CI (99.9%): [11.293, 14.598] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.067 ops/ms
# Warmup Iteration   2: 12.240 ops/ms
# Warmup Iteration   3: 12.641 ops/ms
Iteration   1: 12.483 ops/ms
Iteration   2: 12.808 ops/ms
Iteration   3: 12.915 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.735 ±(99.9%) 4.100 ops/ms [Average]
  (min, avg, max) = (12.483, 12.735, 12.915), stdev = 0.225
  CI (99.9%): [8.636, 16.835] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:42
# Fork: 1 of 1
# Warmup Iteration   1: 6.584 ops/ms
# Warmup Iteration   2: 10.641 ops/ms
# Warmup Iteration   3: 10.956 ops/ms
Iteration   1: 10.969 ops/ms
Iteration   2: 10.936 ops/ms
Iteration   3: 10.981 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.962 ±(99.9%) 0.425 ops/ms [Average]
  (min, avg, max) = (10.936, 10.962, 10.981), stdev = 0.023
  CI (99.9%): [10.537, 11.387] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.064 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.524 ±(99.9%) 0.005 ms/op
Iteration   1: 2.501 ±(99.9%) 0.007 ms/op
Iteration   2: 2.487 ±(99.9%) 0.009 ms/op
Iteration   3: 2.484 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.491 ±(99.9%) 0.164 ms/op [Average]
  (min, avg, max) = (2.484, 2.491, 2.501), stdev = 0.009
  CI (99.9%): [2.327, 2.655] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:33
# Fork: 1 of 1
# Warmup Iteration   1: 3.655 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.439 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.368 ±(99.9%) 0.007 ms/op
Iteration   1: 2.365 ±(99.9%) 0.006 ms/op
Iteration   2: 2.361 ±(99.9%) 0.005 ms/op
Iteration   3: 2.421 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.382 ±(99.9%) 0.615 ms/op [Average]
  (min, avg, max) = (2.361, 2.382, 2.421), stdev = 0.034
  CI (99.9%): [1.767, 2.997] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.009 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.570 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.005 ms/op
Iteration   1: 2.555 ±(99.9%) 0.004 ms/op
Iteration   2: 2.508 ±(99.9%) 0.005 ms/op
Iteration   3: 2.491 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.518 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (2.491, 2.518, 2.555), stdev = 0.033
  CI (99.9%): [1.914, 3.122] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:23
# Fork: 1 of 1
# Warmup Iteration   1: 4.754 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.056 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.013 ±(99.9%) 0.006 ms/op
Iteration   1: 3.012 ±(99.9%) 0.005 ms/op
Iteration   2: 3.034 ±(99.9%) 0.006 ms/op
Iteration   3: 3.055 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.034 ±(99.9%) 0.386 ms/op [Average]
  (min, avg, max) = (3.012, 3.034, 3.055), stdev = 0.021
  CI (99.9%): [2.647, 3.420] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:18
# Fork: 1 of 1
# Warmup Iteration   1: 4.132 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.676 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.006 ms/op
Iteration   1: 2.520 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.719 ms/op
                 createUser·p0.999:  11.637 ms/op
                 createUser·p0.9999: 13.522 ms/op
                 createUser·p1.00:   14.369 ms/op

Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.835 ms/op
                 createUser·p0.50:   2.568 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.871 ms/op
                 createUser·p0.999:  9.862 ms/op
                 createUser·p0.9999: 12.621 ms/op
                 createUser·p1.00:   12.845 ms/op

Iteration   3: 2.511 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.910 ms/op
                 createUser·p0.50:   2.552 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.183 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  9.251 ms/op
                 createUser·p0.9999: 11.924 ms/op
                 createUser·p1.00:   15.188 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 381234
  mean =      2.516 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 73 
    [ 1.250,  2.500) = 184819 
    [ 2.500,  3.750) = 192291 
    [ 3.750,  5.000) = 3221 
    [ 5.000,  6.250) = 336 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 53 
    [10.000, 11.250) = 141 
    [11.250, 12.500) = 108 
    [12.500, 13.750) = 90 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.060 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      9.269 ms/op
     p(99.9900) =     13.189 ms/op
     p(99.9990) =     14.316 ms/op
     p(99.9999) =     15.188 ms/op
    p(100.0000) =     15.188 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.769 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.494 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.385 ±(99.9%) 0.005 ms/op
Iteration   1: 2.369 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.638 ms/op
                 existUser·p0.50:   2.298 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.232 ms/op
                 existUser·p0.99:   3.940 ms/op
                 existUser·p0.999:  7.062 ms/op
                 existUser·p0.9999: 14.795 ms/op
                 existUser·p1.00:   16.564 ms/op

Iteration   2: 2.393 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.823 ms/op
                 existUser·p0.50:   2.331 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.224 ms/op
                 existUser·p0.99:   4.071 ms/op
                 existUser·p0.999:  8.413 ms/op
                 existUser·p0.9999: 13.173 ms/op
                 existUser·p1.00:   14.615 ms/op

Iteration   3: 2.353 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.344 ms/op
                 existUser·p0.50:   2.314 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.731 ms/op
                 existUser·p0.999:  6.377 ms/op
                 existUser·p0.9999: 11.620 ms/op
                 existUser·p1.00:   12.239 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 404441
  mean =      2.372 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 180 
    [ 1.250,  2.500) = 248257 
    [ 2.500,  3.750) = 150252 
    [ 3.750,  5.000) = 4982 
    [ 5.000,  6.250) = 341 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 10 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 119 
    [11.250, 12.500) = 43 
    [12.500, 13.750) = 101 
    [13.750, 15.000) = 56 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.344 ms/op
     p(50.0000) =      2.314 ms/op
     p(90.0000) =      2.986 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.924 ms/op
     p(99.9000) =      6.624 ms/op
     p(99.9900) =     14.369 ms/op
     p(99.9990) =     15.155 ms/op
     p(99.9999) =     16.564 ms/op
    p(100.0000) =     16.564 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.132 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.586 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.544 ±(99.9%) 0.006 ms/op
Iteration   1: 2.562 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.648 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.203 ms/op
                 getUser·p0.95:   3.445 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  11.266 ms/op
                 getUser·p0.9999: 14.501 ms/op
                 getUser·p1.00:   14.893 ms/op

Iteration   2: 2.616 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.802 ms/op
                 getUser·p0.50:   2.589 ms/op
                 getUser·p0.90:   3.215 ms/op
                 getUser·p0.95:   3.457 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  10.912 ms/op
                 getUser·p0.9999: 14.040 ms/op
                 getUser·p1.00:   14.615 ms/op

Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.546 ms/op
                 getUser·p0.50:   2.470 ms/op
                 getUser·p0.90:   3.092 ms/op
                 getUser·p0.95:   3.236 ms/op
                 getUser·p0.99:   3.985 ms/op
                 getUser·p0.999:  8.127 ms/op
                 getUser·p0.9999: 11.399 ms/op
                 getUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 373930
  mean =      2.565 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 153 
    [ 1.250,  2.500) = 185016 
    [ 2.500,  3.750) = 179903 
    [ 3.750,  5.000) = 7516 
    [ 5.000,  6.250) = 829 
    [ 6.250,  7.500) = 120 
    [ 7.500,  8.750) = 24 
    [ 8.750, 10.000) = 39 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 83 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.546 ms/op
     p(50.0000) =      2.515 ms/op
     p(90.0000) =      3.166 ms/op
     p(95.0000) =      3.379 ms/op
     p(99.0000) =      4.227 ms/op
     p(99.9000) =      8.569 ms/op
     p(99.9900) =     14.107 ms/op
     p(99.9990) =     14.652 ms/op
     p(99.9999) =     14.893 ms/op
    p(100.0000) =     14.893 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.699 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.063 ±(99.9%) 0.008 ms/op
Iteration   1: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.482 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.726 ms/op
                 listUser·p0.999:  9.519 ms/op
                 listUser·p0.9999: 10.656 ms/op
                 listUser·p1.00:   12.059 ms/op

Iteration   2: 2.961 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.826 ms/op
                 listUser·p0.50:   2.900 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.472 ms/op
                 listUser·p0.999:  9.045 ms/op
                 listUser·p0.9999: 11.489 ms/op
                 listUser·p1.00:   12.337 ms/op

Iteration   3: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.966 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.883 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.601 ms/op
                 listUser·p0.9999: 13.165 ms/op
                 listUser·p1.00:   15.630 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321532
  mean =      2.983 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 222 
    [ 1.250,  2.500) = 102247 
    [ 2.500,  3.750) = 178794 
    [ 3.750,  5.000) = 33335 
    [ 5.000,  6.250) = 5652 
    [ 6.250,  7.500) = 621 
    [ 7.500,  8.750) = 217 
    [ 8.750, 10.000) = 223 
    [10.000, 11.250) = 166 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.482 ms/op
     p(50.0000) =      2.920 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =      9.363 ms/op
     p(99.9900) =     11.609 ms/op
     p(99.9990) =     14.708 ms/op
     p(99.9999) =     15.630 ms/op
    p(100.0000) =     15.630 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.843 ± 3.655  ops/ms
ClientPb.existUser                       thrpt       3  12.946 ± 1.652  ops/ms
ClientPb.getUser                         thrpt       3  12.735 ± 4.100  ops/ms
ClientPb.listUser                        thrpt       3  10.962 ± 0.425  ops/ms
ClientPb.createUser                       avgt       3   2.491 ± 0.164   ms/op
ClientPb.existUser                        avgt       3   2.382 ± 0.615   ms/op
ClientPb.getUser                          avgt       3   2.518 ± 0.604   ms/op
ClientPb.listUser                         avgt       3   3.034 ± 0.386   ms/op
ClientPb.createUser                     sample  381234   2.516 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.835           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.564           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.183           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.269           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.189           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.188           ms/op
ClientPb.existUser                      sample  404441   2.372 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.344           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.314           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.986           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.191           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.924           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.624           ms/op
ClientPb.existUser:existUser·p0.9999    sample          14.369           ms/op
ClientPb.existUser:existUser·p1.00      sample          16.564           ms/op
ClientPb.getUser                        sample  373930   2.565 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.546           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.515           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.166           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.379           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.227           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.569           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.107           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.893           ms/op
ClientPb.listUser                       sample  321532   2.983 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.482           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.920           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.562           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.363           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.609           ms/op
ClientPb.listUser:listUser·p1.00        sample          15.630           ms/op
