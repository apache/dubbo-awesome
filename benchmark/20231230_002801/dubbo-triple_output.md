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
# Warmup Iteration   1: 5.044 ops/ms
# Warmup Iteration   2: 12.059 ops/ms
# Warmup Iteration   3: 12.120 ops/ms
Iteration   1: 12.400 ops/ms
Iteration   2: 12.448 ops/ms
Iteration   3: 12.479 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.443 ±(99.9%) 0.727 ops/ms [Average]
  (min, avg, max) = (12.400, 12.443, 12.479), stdev = 0.040
  CI (99.9%): [11.715, 13.170] (assumes normal distribution)


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
# Warmup Iteration   1: 8.206 ops/ms
# Warmup Iteration   2: 12.949 ops/ms
# Warmup Iteration   3: 13.078 ops/ms
Iteration   1: 13.113 ops/ms
Iteration   2: 12.884 ops/ms
Iteration   3: 12.998 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.998 ±(99.9%) 2.095 ops/ms [Average]
  (min, avg, max) = (12.884, 12.998, 13.113), stdev = 0.115
  CI (99.9%): [10.903, 15.094] (assumes normal distribution)


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
# Warmup Iteration   1: 7.878 ops/ms
# Warmup Iteration   2: 12.631 ops/ms
# Warmup Iteration   3: 12.875 ops/ms
Iteration   1: 12.947 ops/ms
Iteration   2: 12.623 ops/ms
Iteration   3: 12.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.605 ±(99.9%) 6.410 ops/ms [Average]
  (min, avg, max) = (12.245, 12.605, 12.947), stdev = 0.351
  CI (99.9%): [6.195, 19.015] (assumes normal distribution)


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
# Warmup Iteration   1: 6.771 ops/ms
# Warmup Iteration   2: 10.549 ops/ms
# Warmup Iteration   3: 10.668 ops/ms
Iteration   1: 10.645 ops/ms
Iteration   2: 10.756 ops/ms
Iteration   3: 10.734 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.712 ±(99.9%) 1.068 ops/ms [Average]
  (min, avg, max) = (10.645, 10.712, 10.756), stdev = 0.059
  CI (99.9%): [9.643, 11.780] (assumes normal distribution)


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
# Warmup Iteration   1: 4.090 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 2.617 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.463 ±(99.9%) 0.004 ms/op
Iteration   1: 2.499 ±(99.9%) 0.004 ms/op
Iteration   2: 2.519 ±(99.9%) 0.004 ms/op
Iteration   3: 2.479 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.499 ±(99.9%) 0.361 ms/op [Average]
  (min, avg, max) = (2.479, 2.499, 2.519), stdev = 0.020
  CI (99.9%): [2.138, 2.860] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:32
# Fork: 1 of 1
# Warmup Iteration   1: 3.742 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.428 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.004 ms/op
Iteration   1: 2.449 ±(99.9%) 0.004 ms/op
Iteration   2: 2.441 ±(99.9%) 0.004 ms/op
Iteration   3: 2.451 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.447 ±(99.9%) 0.094 ms/op [Average]
  (min, avg, max) = (2.441, 2.447, 2.451), stdev = 0.005
  CI (99.9%): [2.353, 2.541] (assumes normal distribution)


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
# Warmup Iteration   1: 3.876 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.505 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.487 ±(99.9%) 0.004 ms/op
Iteration   1: 2.478 ±(99.9%) 0.004 ms/op
Iteration   2: 2.476 ±(99.9%) 0.004 ms/op
Iteration   3: 2.464 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.473 ±(99.9%) 0.143 ms/op [Average]
  (min, avg, max) = (2.464, 2.473, 2.478), stdev = 0.008
  CI (99.9%): [2.330, 2.616] (assumes normal distribution)


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
# Warmup Iteration   1: 4.598 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.005 ms/op
Iteration   1: 3.034 ±(99.9%) 0.007 ms/op
Iteration   2: 3.013 ±(99.9%) 0.004 ms/op
Iteration   3: 3.023 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.023 ±(99.9%) 0.187 ms/op [Average]
  (min, avg, max) = (3.013, 3.023, 3.034), stdev = 0.010
  CI (99.9%): [2.836, 3.211] (assumes normal distribution)


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
# Warmup Iteration   1: 4.031 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 2.663 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.474 ±(99.9%) 0.005 ms/op
Iteration   1: 2.515 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.783 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.187 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  11.428 ms/op
                 createUser·p0.9999: 13.334 ms/op
                 createUser·p1.00:   14.139 ms/op

Iteration   2: 2.496 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.912 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.707 ms/op
                 createUser·p0.999:  8.574 ms/op
                 createUser·p0.9999: 11.914 ms/op
                 createUser·p1.00:   12.780 ms/op

Iteration   3: 2.487 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.717 ms/op
                 createUser·p0.50:   2.548 ms/op
                 createUser·p0.90:   3.023 ms/op
                 createUser·p0.95:   3.150 ms/op
                 createUser·p0.99:   3.838 ms/op
                 createUser·p0.999:  8.699 ms/op
                 createUser·p0.9999: 11.198 ms/op
                 createUser·p1.00:   11.420 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 383670
  mean =      2.499 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 45 
    [ 1.250,  2.500) = 187499 
    [ 2.500,  3.750) = 192062 
    [ 3.750,  5.000) = 3168 
    [ 5.000,  6.250) = 390 
    [ 6.250,  7.500) = 44 
    [ 7.500,  8.750) = 85 
    [ 8.750, 10.000) = 134 
    [10.000, 11.250) = 75 
    [11.250, 12.500) = 91 
    [12.500, 13.750) = 75 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.162 ms/op
     p(99.0000) =      3.781 ms/op
     p(99.9000) =      8.591 ms/op
     p(99.9900) =     12.943 ms/op
     p(99.9990) =     13.719 ms/op
     p(99.9999) =     14.139 ms/op
    p(100.0000) =     14.139 ms/op


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
# Warmup Iteration   1: 3.748 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.483 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.460 ±(99.9%) 0.005 ms/op
Iteration   1: 2.454 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.773 ms/op
                 existUser·p0.50:   2.511 ms/op
                 existUser·p0.90:   2.982 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  5.347 ms/op
                 existUser·p0.9999: 14.072 ms/op
                 existUser·p1.00:   14.959 ms/op

Iteration   2: 2.477 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.930 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   3.027 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.674 ms/op
                 existUser·p0.999:  6.416 ms/op
                 existUser·p0.9999: 12.519 ms/op
                 existUser·p1.00:   13.206 ms/op

Iteration   3: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   2.556 ms/op
                 existUser·p0.90:   3.002 ms/op
                 existUser·p0.95:   3.113 ms/op
                 existUser·p0.99:   3.686 ms/op
                 existUser·p0.999:  5.931 ms/op
                 existUser·p0.9999: 12.077 ms/op
                 existUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388719
  mean =      2.467 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 53 
    [ 1.250,  2.500) = 192769 
    [ 2.500,  3.750) = 192797 
    [ 3.750,  5.000) = 2366 
    [ 5.000,  6.250) = 363 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 91 
    [10.000, 11.250) = 68 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 67 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.773 ms/op
     p(50.0000) =      2.519 ms/op
     p(90.0000) =      3.002 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      3.609 ms/op
     p(99.9000) =      6.018 ms/op
     p(99.9900) =     12.962 ms/op
     p(99.9990) =     14.738 ms/op
     p(99.9999) =     14.959 ms/op
    p(100.0000) =     14.959 ms/op


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
# Warmup Iteration   1: 3.959 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 2.550 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.526 ±(99.9%) 0.006 ms/op
Iteration   1: 2.499 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.031 ms/op
                 getUser·p0.95:   3.178 ms/op
                 getUser·p0.99:   4.202 ms/op
                 getUser·p0.999:  10.983 ms/op
                 getUser·p0.9999: 13.265 ms/op
                 getUser·p1.00:   14.402 ms/op

Iteration   2: 2.525 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.568 ms/op
                 getUser·p0.50:   2.560 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.281 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  9.634 ms/op
                 getUser·p0.9999: 11.993 ms/op
                 getUser·p1.00:   12.272 ms/op

Iteration   3: 2.472 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.539 ms/op
                 getUser·p0.50:   2.494 ms/op
                 getUser·p0.90:   3.015 ms/op
                 getUser·p0.95:   3.125 ms/op
                 getUser·p0.99:   3.654 ms/op
                 getUser·p0.999:  5.813 ms/op
                 getUser·p0.9999: 11.119 ms/op
                 getUser·p1.00:   12.009 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383909
  mean =      2.498 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 188866 
    [ 2.500,  3.750) = 188697 
    [ 3.750,  5.000) = 4807 
    [ 5.000,  6.250) = 913 
    [ 6.250,  7.500) = 125 
    [ 7.500,  8.750) = 34 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 93 
    [11.250, 12.500) = 133 
    [12.500, 13.750) = 45 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.539 ms/op
     p(50.0000) =      2.540 ms/op
     p(90.0000) =      3.039 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      4.157 ms/op
     p(99.9000) =      8.618 ms/op
     p(99.9900) =     12.681 ms/op
     p(99.9990) =     13.833 ms/op
     p(99.9999) =     14.402 ms/op
    p(100.0000) =     14.402 ms/op


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
# Warmup Iteration   1: 4.728 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.028 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.998 ±(99.9%) 0.009 ms/op
Iteration   1: 2.975 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.868 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.830 ms/op
                 listUser·p0.95:   4.284 ms/op
                 listUser·p0.99:   5.382 ms/op
                 listUser·p0.999:  8.823 ms/op
                 listUser·p0.9999: 10.699 ms/op
                 listUser·p1.00:   11.305 ms/op

Iteration   2: 2.982 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.874 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.465 ms/op
                 listUser·p0.999:  9.398 ms/op
                 listUser·p0.9999: 11.162 ms/op
                 listUser·p1.00:   11.600 ms/op

Iteration   3: 2.993 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.868 ms/op
                 listUser·p0.50:   2.920 ms/op
                 listUser·p0.90:   3.879 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   5.620 ms/op
                 listUser·p0.999:  10.355 ms/op
                 listUser·p0.9999: 12.980 ms/op
                 listUser·p1.00:   13.926 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 321485
  mean =      2.983 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 119 
    [ 1.250,  2.500) = 97325 
    [ 2.500,  3.750) = 186741 
    [ 3.750,  5.000) = 30705 
    [ 5.000,  6.250) = 5410 
    [ 6.250,  7.500) = 563 
    [ 7.500,  8.750) = 145 
    [ 8.750, 10.000) = 258 
    [10.000, 11.250) = 159 
    [11.250, 12.500) = 38 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 4 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.868 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.497 ms/op
     p(99.9000) =      9.552 ms/op
     p(99.9900) =     11.698 ms/op
     p(99.9990) =     13.834 ms/op
     p(99.9999) =     13.926 ms/op
    p(100.0000) =     13.926 ms/op


# Run complete. Total time: 00:12:57

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.443 ± 0.727  ops/ms
ClientPb.existUser                       thrpt       3  12.998 ± 2.095  ops/ms
ClientPb.getUser                         thrpt       3  12.605 ± 6.410  ops/ms
ClientPb.listUser                        thrpt       3  10.712 ± 1.068  ops/ms
ClientPb.createUser                       avgt       3   2.499 ± 0.361   ms/op
ClientPb.existUser                        avgt       3   2.447 ± 0.094   ms/op
ClientPb.getUser                          avgt       3   2.473 ± 0.143   ms/op
ClientPb.listUser                         avgt       3   3.023 ± 0.187   ms/op
ClientPb.createUser                     sample  383670   2.499 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.717           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.039           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.162           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.781           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.591           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.943           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.139           ms/op
ClientPb.existUser                      sample  388719   2.467 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.773           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.519           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.002           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.609           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.018           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.962           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.959           ms/op
ClientPb.getUser                        sample  383909   2.498 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.539           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.540           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.039           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.157           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.618           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.681           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.402           ms/op
ClientPb.listUser                       sample  321485   2.983 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.868           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.497           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.552           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.698           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.926           ms/op
