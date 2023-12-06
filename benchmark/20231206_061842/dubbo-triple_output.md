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
# Warmup Iteration   1: 4.578 ops/ms
# Warmup Iteration   2: 12.108 ops/ms
# Warmup Iteration   3: 12.285 ops/ms
Iteration   1: 12.414 ops/ms
Iteration   2: 12.497 ops/ms
Iteration   3: 12.602 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.504 ±(99.9%) 1.725 ops/ms [Average]
  (min, avg, max) = (12.414, 12.504, 12.602), stdev = 0.095
  CI (99.9%): [10.779, 14.229] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 7.725 ops/ms
# Warmup Iteration   2: 12.973 ops/ms
# Warmup Iteration   3: 12.924 ops/ms
Iteration   1: 12.998 ops/ms
Iteration   2: 12.845 ops/ms
Iteration   3: 12.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.913 ±(99.9%) 1.430 ops/ms [Average]
  (min, avg, max) = (12.845, 12.913, 12.998), stdev = 0.078
  CI (99.9%): [11.483, 14.343] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.982 ops/ms
# Warmup Iteration   2: 12.647 ops/ms
# Warmup Iteration   3: 12.829 ops/ms
Iteration   1: 12.699 ops/ms
Iteration   2: 12.721 ops/ms
Iteration   3: 12.822 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.748 ±(99.9%) 1.200 ops/ms [Average]
  (min, avg, max) = (12.699, 12.748, 12.822), stdev = 0.066
  CI (99.9%): [11.548, 13.947] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.555 ops/ms
# Warmup Iteration   2: 10.497 ops/ms
# Warmup Iteration   3: 10.440 ops/ms
Iteration   1: 10.609 ops/ms
Iteration   2: 10.588 ops/ms
Iteration   3: 10.588 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.595 ±(99.9%) 0.217 ops/ms [Average]
  (min, avg, max) = (10.588, 10.595, 10.609), stdev = 0.012
  CI (99.9%): [10.378, 10.812] (assumes normal distribution)


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
# Warmup Iteration   1: 4.116 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.554 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.522 ±(99.9%) 0.004 ms/op
Iteration   1: 2.543 ±(99.9%) 0.004 ms/op
Iteration   2: 2.503 ±(99.9%) 0.004 ms/op
Iteration   3: 2.509 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.518 ±(99.9%) 0.391 ms/op [Average]
  (min, avg, max) = (2.503, 2.518, 2.543), stdev = 0.021
  CI (99.9%): [2.127, 2.909] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.814 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.476 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.005 ms/op
Iteration   1: 2.488 ±(99.9%) 0.004 ms/op
Iteration   2: 2.480 ±(99.9%) 0.004 ms/op
Iteration   3: 2.486 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.485 ±(99.9%) 0.080 ms/op [Average]
  (min, avg, max) = (2.480, 2.485, 2.488), stdev = 0.004
  CI (99.9%): [2.405, 2.565] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.903 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.596 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.504 ±(99.9%) 0.005 ms/op
Iteration   1: 2.514 ±(99.9%) 0.004 ms/op
Iteration   2: 2.559 ±(99.9%) 0.004 ms/op
Iteration   3: 2.494 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.522 ±(99.9%) 0.604 ms/op [Average]
  (min, avg, max) = (2.494, 2.522, 2.559), stdev = 0.033
  CI (99.9%): [1.919, 3.126] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.669 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.067 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.018 ±(99.9%) 0.006 ms/op
Iteration   1: 3.004 ±(99.9%) 0.006 ms/op
Iteration   2: 2.999 ±(99.9%) 0.005 ms/op
Iteration   3: 2.989 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.997 ±(99.9%) 0.139 ms/op [Average]
  (min, avg, max) = (2.989, 2.997, 3.004), stdev = 0.008
  CI (99.9%): [2.858, 3.136] (assumes normal distribution)


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
# Warmup Iteration   1: 4.234 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 2.662 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.537 ±(99.9%) 0.006 ms/op
Iteration   1: 2.530 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.942 ms/op
                 createUser·p0.50:   2.589 ms/op
                 createUser·p0.90:   3.072 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.789 ms/op
                 createUser·p0.999:  12.440 ms/op
                 createUser·p0.9999: 14.621 ms/op
                 createUser·p1.00:   14.942 ms/op

Iteration   2: 2.534 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.982 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.170 ms/op
                 createUser·p0.99:   4.092 ms/op
                 createUser·p0.999:  10.186 ms/op
                 createUser·p0.9999: 14.512 ms/op
                 createUser·p1.00:   15.450 ms/op

Iteration   3: 2.538 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.771 ms/op
                 createUser·p0.50:   2.605 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.211 ms/op
                 createUser·p0.99:   4.014 ms/op
                 createUser·p0.999:  8.503 ms/op
                 createUser·p0.9999: 10.289 ms/op
                 createUser·p1.00:   11.010 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 378431
  mean =      2.534 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 181501 
    [ 2.500,  3.750) = 191858 
    [ 3.750,  5.000) = 3918 
    [ 5.000,  6.250) = 589 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 51 
    [ 8.750, 10.000) = 84 
    [10.000, 11.250) = 81 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 87 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      2.601 ms/op
     p(90.0000) =      3.072 ms/op
     p(95.0000) =      3.195 ms/op
     p(99.0000) =      3.920 ms/op
     p(99.9000) =      8.538 ms/op
     p(99.9900) =     14.388 ms/op
     p(99.9990) =     15.368 ms/op
     p(99.9999) =     15.450 ms/op
    p(100.0000) =     15.450 ms/op


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
# Warmup Iteration   1: 3.757 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.464 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.450 ±(99.9%) 0.005 ms/op
Iteration   1: 2.475 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.000 ms/op
                 existUser·p0.50:   2.517 ms/op
                 existUser·p0.90:   3.011 ms/op
                 existUser·p0.95:   3.142 ms/op
                 existUser·p0.99:   3.883 ms/op
                 existUser·p0.999:  11.826 ms/op
                 existUser·p0.9999: 13.435 ms/op
                 existUser·p1.00:   13.615 ms/op

Iteration   2: 2.489 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.933 ms/op
                 existUser·p0.50:   2.609 ms/op
                 existUser·p0.90:   3.019 ms/op
                 existUser·p0.95:   3.128 ms/op
                 existUser·p0.99:   3.568 ms/op
                 existUser·p0.999:  6.217 ms/op
                 existUser·p0.9999: 12.932 ms/op
                 existUser·p1.00:   13.681 ms/op

Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.839 ms/op
                 existUser·p0.50:   2.486 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.105 ms/op
                 existUser·p0.99:   3.700 ms/op
                 existUser·p0.999:  5.607 ms/op
                 existUser·p0.9999: 12.780 ms/op
                 existUser·p1.00:   13.713 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388164
  mean =      2.471 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 52 
    [ 1.250,  2.500) = 191726 
    [ 2.500,  3.750) = 192658 
    [ 3.750,  5.000) = 2829 
    [ 5.000,  6.250) = 486 
    [ 6.250,  7.500) = 84 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 38 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 113 
    [12.500, 13.750) = 123 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.839 ms/op
     p(50.0000) =      2.527 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.719 ms/op
     p(99.9000) =      6.413 ms/op
     p(99.9900) =     13.025 ms/op
     p(99.9990) =     13.586 ms/op
     p(99.9999) =     13.713 ms/op
    p(100.0000) =     13.713 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.909 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 2.582 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.518 ±(99.9%) 0.006 ms/op
Iteration   1: 2.490 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   2.503 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   3.898 ms/op
                 getUser·p0.999:  9.500 ms/op
                 getUser·p0.9999: 14.715 ms/op
                 getUser·p1.00:   14.942 ms/op

Iteration   2: 2.488 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.940 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.035 ms/op
                 getUser·p0.95:   3.162 ms/op
                 getUser·p0.99:   3.797 ms/op
                 getUser·p0.999:  7.768 ms/op
                 getUser·p0.9999: 14.456 ms/op
                 getUser·p1.00:   15.139 ms/op

Iteration   3: 2.520 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.017 ms/op
                 getUser·p0.50:   2.535 ms/op
                 getUser·p0.90:   3.080 ms/op
                 getUser·p0.95:   3.269 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  9.699 ms/op
                 getUser·p0.9999: 13.063 ms/op
                 getUser·p1.00:   14.205 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 383835
  mean =      2.499 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 190734 
    [ 2.500,  3.750) = 187316 
    [ 3.750,  5.000) = 4585 
    [ 5.000,  6.250) = 696 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 30 
    [10.000, 11.250) = 108 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 93 
    [13.750, 15.000) = 83 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.940 ms/op
     p(50.0000) =      2.511 ms/op
     p(90.0000) =      3.047 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      4.002 ms/op
     p(99.9000) =      9.104 ms/op
     p(99.9900) =     14.412 ms/op
     p(99.9990) =     14.942 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.855 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.085 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.041 ±(99.9%) 0.009 ms/op
Iteration   1: 3.038 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.937 ms/op
                 listUser·p0.50:   2.966 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.481 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  8.798 ms/op
                 listUser·p0.9999: 10.344 ms/op
                 listUser·p1.00:   10.715 ms/op

Iteration   2: 3.038 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.972 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.932 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.554 ms/op
                 listUser·p0.999:  9.446 ms/op
                 listUser·p0.9999: 11.092 ms/op
                 listUser·p1.00:   11.665 ms/op

Iteration   3: 3.026 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.922 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   3.920 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.497 ms/op
                 listUser·p0.999:  9.880 ms/op
                 listUser·p0.9999: 11.214 ms/op
                 listUser·p1.00:   11.878 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316104
  mean =      3.034 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 117 
    [ 1.250,  2.500) = 87427 
    [ 2.500,  3.750) = 187407 
    [ 3.750,  5.000) = 33884 
    [ 5.000,  6.250) = 5893 
    [ 6.250,  7.500) = 654 
    [ 7.500,  8.750) = 272 
    [ 8.750, 10.000) = 288 
    [10.000, 11.250) = 148 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      5.554 ms/op
     p(99.9000) =      9.372 ms/op
     p(99.9900) =     10.961 ms/op
     p(99.9990) =     11.758 ms/op
     p(99.9999) =     11.878 ms/op
    p(100.0000) =     11.878 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.504 ± 1.725  ops/ms
ClientPb.existUser                       thrpt       3  12.913 ± 1.430  ops/ms
ClientPb.getUser                         thrpt       3  12.748 ± 1.200  ops/ms
ClientPb.listUser                        thrpt       3  10.595 ± 0.217  ops/ms
ClientPb.createUser                       avgt       3   2.518 ± 0.391   ms/op
ClientPb.existUser                        avgt       3   2.485 ± 0.080   ms/op
ClientPb.getUser                          avgt       3   2.522 ± 0.604   ms/op
ClientPb.listUser                         avgt       3   2.997 ± 0.139   ms/op
ClientPb.createUser                     sample  378431   2.534 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.771           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.601           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.072           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.195           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.920           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.538           ms/op
ClientPb.createUser:createUser·p0.9999  sample          14.388           ms/op
ClientPb.createUser:createUser·p1.00    sample          15.450           ms/op
ClientPb.existUser                      sample  388164   2.471 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.839           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.527           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.006           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.125           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.719           ms/op
ClientPb.existUser:existUser·p0.999     sample           6.413           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.025           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.713           ms/op
ClientPb.getUser                        sample  383835   2.499 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.940           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.511           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.047           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.203           ms/op
ClientPb.getUser:getUser·p0.99          sample           4.002           ms/op
ClientPb.getUser:getUser·p0.999         sample           9.104           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.412           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.139           ms/op
ClientPb.listUser                       sample  316104   3.034 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.922           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.970           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.928           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.554           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.372           ms/op
ClientPb.listUser:listUser·p0.9999      sample          10.961           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.878           ms/op
