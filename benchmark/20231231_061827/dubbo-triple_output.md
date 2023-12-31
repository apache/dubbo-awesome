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
# Warmup Iteration   1: 5.287 ops/ms
# Warmup Iteration   2: 12.231 ops/ms
# Warmup Iteration   3: 12.729 ops/ms
Iteration   1: 12.719 ops/ms
Iteration   2: 12.849 ops/ms
Iteration   3: 12.835 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.801 ±(99.9%) 1.309 ops/ms [Average]
  (min, avg, max) = (12.719, 12.801, 12.849), stdev = 0.072
  CI (99.9%): [11.492, 14.110] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 8.077 ops/ms
# Warmup Iteration   2: 13.416 ops/ms
# Warmup Iteration   3: 13.185 ops/ms
Iteration   1: 13.150 ops/ms
Iteration   2: 13.098 ops/ms
Iteration   3: 13.109 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.119 ±(99.9%) 0.498 ops/ms [Average]
  (min, avg, max) = (13.098, 13.119, 13.150), stdev = 0.027
  CI (99.9%): [12.621, 13.617] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.589 ops/ms
# Warmup Iteration   2: 12.731 ops/ms
# Warmup Iteration   3: 12.878 ops/ms
Iteration   1: 12.991 ops/ms
Iteration   2: 12.876 ops/ms
Iteration   3: 12.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.880 ±(99.9%) 1.996 ops/ms [Average]
  (min, avg, max) = (12.772, 12.880, 12.991), stdev = 0.109
  CI (99.9%): [10.883, 14.876] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 6.589 ops/ms
# Warmup Iteration   2: 10.608 ops/ms
# Warmup Iteration   3: 10.633 ops/ms
Iteration   1: 10.766 ops/ms
Iteration   2: 10.542 ops/ms
Iteration   3: 10.776 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.695 ±(99.9%) 2.418 ops/ms [Average]
  (min, avg, max) = (10.542, 10.695, 10.776), stdev = 0.133
  CI (99.9%): [8.277, 13.112] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.214 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.510 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.004 ms/op
Iteration   1: 2.528 ±(99.9%) 0.004 ms/op
Iteration   2: 2.479 ±(99.9%) 0.003 ms/op
Iteration   3: 2.451 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.486 ±(99.9%) 0.714 ms/op [Average]
  (min, avg, max) = (2.451, 2.486, 2.528), stdev = 0.039
  CI (99.9%): [1.772, 3.200] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.785 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.445 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.433 ±(99.9%) 0.003 ms/op
Iteration   1: 2.417 ±(99.9%) 0.003 ms/op
Iteration   2: 2.448 ±(99.9%) 0.004 ms/op
Iteration   3: 2.424 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.429 ±(99.9%) 0.296 ms/op [Average]
  (min, avg, max) = (2.417, 2.429, 2.448), stdev = 0.016
  CI (99.9%): [2.133, 2.725] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.806 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.516 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.481 ±(99.9%) 0.004 ms/op
Iteration   1: 2.458 ±(99.9%) 0.004 ms/op
Iteration   2: 2.478 ±(99.9%) 0.004 ms/op
Iteration   3: 2.477 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.471 ±(99.9%) 0.201 ms/op [Average]
  (min, avg, max) = (2.458, 2.471, 2.478), stdev = 0.011
  CI (99.9%): [2.270, 2.672] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.585 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.992 ±(99.9%) 0.005 ms/op
Iteration   1: 2.991 ±(99.9%) 0.004 ms/op
Iteration   2: 2.968 ±(99.9%) 0.007 ms/op
Iteration   3: 2.977 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.978 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (2.968, 2.978, 2.991), stdev = 0.011
  CI (99.9%): [2.770, 3.187] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.250 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 2.679 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.523 ±(99.9%) 0.006 ms/op
Iteration   1: 2.527 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.958 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.076 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.777 ms/op
                 createUser·p0.999:  10.920 ms/op
                 createUser·p0.9999: 13.725 ms/op
                 createUser·p1.00:   14.352 ms/op

Iteration   2: 2.517 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.950 ms/op
                 createUser·p0.50:   2.560 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  8.879 ms/op
                 createUser·p0.9999: 12.571 ms/op
                 createUser·p1.00:   12.845 ms/op

Iteration   3: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   3.785 ms/op
                 createUser·p0.999:  8.581 ms/op
                 createUser·p0.9999: 11.031 ms/op
                 createUser·p1.00:   11.436 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 380646
  mean =      2.520 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 60 
    [ 1.250,  2.500) = 185981 
    [ 2.500,  3.750) = 190798 
    [ 3.750,  5.000) = 3103 
    [ 5.000,  6.250) = 305 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 82 
    [10.000, 11.250) = 111 
    [11.250, 12.500) = 106 
    [12.500, 13.750) = 62 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.901 ms/op
     p(50.0000) =      2.552 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.752 ms/op
     p(99.9000) =      8.597 ms/op
     p(99.9900) =     12.974 ms/op
     p(99.9990) =     14.257 ms/op
     p(99.9999) =     14.352 ms/op
    p(100.0000) =     14.352 ms/op


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
# Warmup Iteration   1: 3.601 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 2.435 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.405 ±(99.9%) 0.005 ms/op
Iteration   1: 2.418 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.762 ms/op
                 existUser·p0.50:   2.482 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.047 ms/op
                 existUser·p0.99:   3.625 ms/op
                 existUser·p0.999:  5.245 ms/op
                 existUser·p0.9999: 13.677 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   2: 2.408 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.029 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.908 ms/op
                 existUser·p0.95:   2.986 ms/op
                 existUser·p0.99:   3.318 ms/op
                 existUser·p0.999:  5.491 ms/op
                 existUser·p0.9999: 13.164 ms/op
                 existUser·p1.00:   13.517 ms/op

Iteration   3: 2.429 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.812 ms/op
                 existUser·p0.50:   2.484 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   4.030 ms/op
                 existUser·p0.999:  6.942 ms/op
                 existUser·p0.9999: 11.796 ms/op
                 existUser·p1.00:   12.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396582
  mean =      2.418 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 198164 
    [ 2.500,  3.750) = 194741 
    [ 3.750,  5.000) = 2984 
    [ 5.000,  6.250) = 265 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 99 
    [12.500, 13.750) = 82 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.762 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.933 ms/op
     p(95.0000) =      3.035 ms/op
     p(99.0000) =      3.679 ms/op
     p(99.9000) =      5.799 ms/op
     p(99.9900) =     13.381 ms/op
     p(99.9990) =     14.173 ms/op
     p(99.9999) =     14.303 ms/op
    p(100.0000) =     14.303 ms/op


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
# Warmup Iteration   1: 3.845 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.514 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.480 ±(99.9%) 0.005 ms/op
Iteration   1: 2.458 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.949 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.748 ms/op
                 getUser·p0.999:  6.370 ms/op
                 getUser·p0.9999: 13.238 ms/op
                 getUser·p1.00:   14.270 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.995 ms/op
                 getUser·p0.50:   2.511 ms/op
                 getUser·p0.90:   3.006 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.236 ms/op
                 getUser·p0.9999: 12.062 ms/op
                 getUser·p1.00:   12.763 ms/op

Iteration   3: 2.456 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.918 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   2.994 ms/op
                 getUser·p0.95:   3.101 ms/op
                 getUser·p0.99:   3.731 ms/op
                 getUser·p0.999:  8.059 ms/op
                 getUser·p0.9999: 10.715 ms/op
                 getUser·p1.00:   11.092 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 389320
  mean =      2.464 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 195422 
    [ 2.500,  3.750) = 189310 
    [ 3.750,  5.000) = 3657 
    [ 5.000,  6.250) = 441 
    [ 6.250,  7.500) = 22 
    [ 7.500,  8.750) = 55 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 90 
    [11.250, 12.500) = 117 
    [12.500, 13.750) = 60 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      2.490 ms/op
     p(90.0000) =      2.994 ms/op
     p(95.0000) =      3.117 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =      7.889 ms/op
     p(99.9900) =     12.929 ms/op
     p(99.9990) =     13.337 ms/op
     p(99.9999) =     14.270 ms/op
    p(100.0000) =     14.270 ms/op


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
# Warmup Iteration   1: 4.893 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.057 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.014 ±(99.9%) 0.008 ms/op
Iteration   1: 3.016 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.848 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.916 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.961 ms/op
                 listUser·p0.9999: 12.284 ms/op
                 listUser·p1.00:   13.468 ms/op

Iteration   2: 2.988 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.950 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.842 ms/op
                 listUser·p0.95:   4.276 ms/op
                 listUser·p0.99:   5.399 ms/op
                 listUser·p0.999:  9.322 ms/op
                 listUser·p0.9999: 10.751 ms/op
                 listUser·p1.00:   11.764 ms/op

Iteration   3: 3.007 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   2.945 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.636 ms/op
                 listUser·p0.999:  9.301 ms/op
                 listUser·p0.9999: 10.870 ms/op
                 listUser·p1.00:   13.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 319253
  mean =      3.004 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 92718 
    [ 2.500,  3.750) = 187480 
    [ 3.750,  5.000) = 31792 
    [ 5.000,  6.250) = 5707 
    [ 6.250,  7.500) = 723 
    [ 7.500,  8.750) = 208 
    [ 8.750, 10.000) = 309 
    [10.000, 11.250) = 169 
    [11.250, 12.500) = 17 
    [12.500, 13.750) = 13 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.383 ms/op
     p(99.0000) =      5.571 ms/op
     p(99.9000) =      9.470 ms/op
     p(99.9900) =     11.224 ms/op
     p(99.9990) =     13.157 ms/op
     p(99.9999) =     13.468 ms/op
    p(100.0000) =     13.468 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.801 ± 1.309  ops/ms
ClientPb.existUser                       thrpt       3  13.119 ± 0.498  ops/ms
ClientPb.getUser                         thrpt       3  12.880 ± 1.996  ops/ms
ClientPb.listUser                        thrpt       3  10.695 ± 2.418  ops/ms
ClientPb.createUser                       avgt       3   2.486 ± 0.714   ms/op
ClientPb.existUser                        avgt       3   2.429 ± 0.296   ms/op
ClientPb.getUser                          avgt       3   2.471 ± 0.201   ms/op
ClientPb.listUser                         avgt       3   2.978 ± 0.209   ms/op
ClientPb.createUser                     sample  380646   2.520 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.901           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.552           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.064           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.752           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.597           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.974           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.352           ms/op
ClientPb.existUser                      sample  396582   2.418 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.762           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.933           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.035           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.679           ms/op
ClientPb.existUser:existUser·p0.999     sample           5.799           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.381           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.303           ms/op
ClientPb.getUser                        sample  389320   2.464 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.918           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.490           ms/op
ClientPb.getUser:getUser·p0.90          sample           2.994           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.854           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.889           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.929           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.270           ms/op
ClientPb.listUser                       sample  319253   3.004 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.848           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.933           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.883           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.571           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.470           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.224           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.468           ms/op
