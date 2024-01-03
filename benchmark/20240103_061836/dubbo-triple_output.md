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
# Warmup Iteration   1: 5.201 ops/ms
# Warmup Iteration   2: 12.128 ops/ms
# Warmup Iteration   3: 12.556 ops/ms
Iteration   1: 12.680 ops/ms
Iteration   2: 12.714 ops/ms
Iteration   3: 12.742 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.712 ±(99.9%) 0.565 ops/ms [Average]
  (min, avg, max) = (12.680, 12.712, 12.742), stdev = 0.031
  CI (99.9%): [12.147, 13.277] (assumes normal distribution)


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
# Warmup Iteration   1: 8.100 ops/ms
# Warmup Iteration   2: 13.116 ops/ms
# Warmup Iteration   3: 13.160 ops/ms
Iteration   1: 13.159 ops/ms
Iteration   2: 13.100 ops/ms
Iteration   3: 13.004 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.088 ±(99.9%) 1.422 ops/ms [Average]
  (min, avg, max) = (13.004, 13.088, 13.159), stdev = 0.078
  CI (99.9%): [11.665, 14.510] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.778 ops/ms
# Warmup Iteration   2: 12.549 ops/ms
# Warmup Iteration   3: 12.959 ops/ms
Iteration   1: 12.978 ops/ms
Iteration   2: 12.761 ops/ms
Iteration   3: 12.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.887 ±(99.9%) 2.056 ops/ms [Average]
  (min, avg, max) = (12.761, 12.887, 12.978), stdev = 0.113
  CI (99.9%): [10.831, 14.944] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:44
# Fork: 1 of 1
# Warmup Iteration   1: 6.921 ops/ms
# Warmup Iteration   2: 10.565 ops/ms
# Warmup Iteration   3: 10.689 ops/ms
Iteration   1: 10.688 ops/ms
Iteration   2: 10.649 ops/ms
Iteration   3: 10.725 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.687 ±(99.9%) 0.688 ops/ms [Average]
  (min, avg, max) = (10.649, 10.687, 10.725), stdev = 0.038
  CI (99.9%): [10.000, 11.375] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.014 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.509 ±(99.9%) 0.004 ms/op
Iteration   1: 2.547 ±(99.9%) 0.004 ms/op
Iteration   2: 2.536 ±(99.9%) 0.003 ms/op
Iteration   3: 2.531 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.538 ±(99.9%) 0.152 ms/op [Average]
  (min, avg, max) = (2.531, 2.538, 2.547), stdev = 0.008
  CI (99.9%): [2.387, 2.690] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.733 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.430 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.431 ±(99.9%) 0.004 ms/op
Iteration   1: 2.448 ±(99.9%) 0.004 ms/op
Iteration   2: 2.422 ±(99.9%) 0.004 ms/op
Iteration   3: 2.443 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.438 ±(99.9%) 0.255 ms/op [Average]
  (min, avg, max) = (2.422, 2.438, 2.448), stdev = 0.014
  CI (99.9%): [2.183, 2.692] (assumes normal distribution)


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
# Warmup Iteration   1: 3.703 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 2.530 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.492 ±(99.9%) 0.004 ms/op
Iteration   1: 2.492 ±(99.9%) 0.005 ms/op
Iteration   2: 2.480 ±(99.9%) 0.003 ms/op
Iteration   3: 2.468 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.480 ±(99.9%) 0.221 ms/op [Average]
  (min, avg, max) = (2.468, 2.480, 2.492), stdev = 0.012
  CI (99.9%): [2.259, 2.701] (assumes normal distribution)


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
# Warmup Iteration   1: 4.554 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.993 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.006 ms/op
Iteration   1: 2.956 ±(99.9%) 0.004 ms/op
Iteration   2: 2.961 ±(99.9%) 0.004 ms/op
Iteration   3: 2.938 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  2.951 ±(99.9%) 0.218 ms/op [Average]
  (min, avg, max) = (2.938, 2.951, 2.961), stdev = 0.012
  CI (99.9%): [2.733, 3.170] (assumes normal distribution)


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
# Warmup Iteration   1: 4.012 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.555 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.490 ±(99.9%) 0.005 ms/op
Iteration   1: 2.497 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.018 ms/op
                 createUser·p0.50:   2.544 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.174 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  10.075 ms/op
                 createUser·p0.9999: 13.638 ms/op
                 createUser·p1.00:   13.877 ms/op

Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.040 ms/op
                 createUser·p0.50:   2.564 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.101 ms/op
                 createUser·p0.99:   3.552 ms/op
                 createUser·p0.999:  6.547 ms/op
                 createUser·p0.9999: 12.355 ms/op
                 createUser·p1.00:   12.567 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.969 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.703 ms/op
                 createUser·p0.999:  8.713 ms/op
                 createUser·p0.9999: 11.010 ms/op
                 createUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 385438
  mean =      2.488 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 188227 
    [ 2.500,  3.750) = 192953 
    [ 3.750,  5.000) = 3489 
    [ 5.000,  6.250) = 293 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 147 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 49 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.969 ms/op
     p(50.0000) =      2.548 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      3.808 ms/op
     p(99.9000) =      8.621 ms/op
     p(99.9900) =     12.763 ms/op
     p(99.9990) =     13.819 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 3.732 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.474 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.429 ±(99.9%) 0.005 ms/op
Iteration   1: 2.429 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   2.523 ms/op
                 existUser·p0.90:   2.945 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.461 ms/op
                 existUser·p0.999:  5.788 ms/op
                 existUser·p0.9999: 15.221 ms/op
                 existUser·p1.00:   15.319 ms/op

Iteration   2: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.991 ms/op
                 existUser·p0.50:   2.515 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.035 ms/op
                 existUser·p0.99:   3.389 ms/op
                 existUser·p0.999:  7.542 ms/op
                 existUser·p0.9999: 11.973 ms/op
                 existUser·p1.00:   12.927 ms/op

Iteration   3: 2.407 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.826 ms/op
                 existUser·p0.50:   2.425 ms/op
                 existUser·p0.90:   2.953 ms/op
                 existUser·p0.95:   3.080 ms/op
                 existUser·p0.99:   3.580 ms/op
                 existUser·p0.999:  6.424 ms/op
                 existUser·p0.9999: 11.902 ms/op
                 existUser·p1.00:   12.501 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 396567
  mean =      2.418 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 51 
    [ 1.250,  2.500) = 200724 
    [ 2.500,  3.750) = 193351 
    [ 3.750,  5.000) = 1886 
    [ 5.000,  6.250) = 117 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 44 
    [ 8.750, 10.000) = 73 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 132 
    [12.500, 13.750) = 34 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.826 ms/op
     p(50.0000) =      2.478 ms/op
     p(90.0000) =      2.945 ms/op
     p(95.0000) =      3.047 ms/op
     p(99.0000) =      3.486 ms/op
     p(99.9000) =      7.081 ms/op
     p(99.9900) =     12.971 ms/op
     p(99.9990) =     15.270 ms/op
     p(99.9999) =     15.319 ms/op
    p(100.0000) =     15.319 ms/op


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
# Warmup Iteration   1: 3.826 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.527 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.459 ±(99.9%) 0.006 ms/op
Iteration   1: 2.471 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.896 ms/op
                 getUser·p0.50:   2.474 ms/op
                 getUser·p0.90:   3.011 ms/op
                 getUser·p0.95:   3.117 ms/op
                 getUser·p0.99:   3.637 ms/op
                 getUser·p0.999:  6.369 ms/op
                 getUser·p0.9999: 13.553 ms/op
                 getUser·p1.00:   14.418 ms/op

Iteration   2: 2.475 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.810 ms/op
                 getUser·p0.50:   2.490 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.826 ms/op
                 getUser·p0.999:  7.771 ms/op
                 getUser·p0.9999: 12.502 ms/op
                 getUser·p1.00:   12.829 ms/op

Iteration   3: 2.457 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.783 ms/op
                 getUser·p0.50:   2.478 ms/op
                 getUser·p0.90:   2.990 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   3.645 ms/op
                 getUser·p0.999:  6.514 ms/op
                 getUser·p0.9999: 11.403 ms/op
                 getUser·p1.00:   13.582 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 388666
  mean =      2.468 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 195882 
    [ 2.500,  3.750) = 189105 
    [ 3.750,  5.000) = 2759 
    [ 5.000,  6.250) = 452 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 65 
    [ 8.750, 10.000) = 50 
    [10.000, 11.250) = 51 
    [11.250, 12.500) = 129 
    [12.500, 13.750) = 84 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.783 ms/op
     p(50.0000) =      2.482 ms/op
     p(90.0000) =      3.006 ms/op
     p(95.0000) =      3.121 ms/op
     p(99.0000) =      3.711 ms/op
     p(99.9000) =      7.081 ms/op
     p(99.9900) =     12.960 ms/op
     p(99.9990) =     13.901 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


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
# Warmup Iteration   1: 4.817 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.008 ms/op
Iteration   1: 3.009 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.860 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.891 ms/op
                 listUser·p0.95:   4.407 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  10.580 ms/op
                 listUser·p0.9999: 19.726 ms/op
                 listUser·p1.00:   21.037 ms/op

Iteration   2: 2.975 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.897 ms/op
                 listUser·p0.50:   2.916 ms/op
                 listUser·p0.90:   3.838 ms/op
                 listUser·p0.95:   4.301 ms/op
                 listUser·p0.99:   5.448 ms/op
                 listUser·p0.999:  9.482 ms/op
                 listUser·p0.9999: 12.173 ms/op
                 listUser·p1.00:   12.337 ms/op

Iteration   3: 2.980 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.995 ms/op
                 listUser·p0.50:   2.925 ms/op
                 listUser·p0.90:   3.822 ms/op
                 listUser·p0.95:   4.268 ms/op
                 listUser·p0.99:   5.374 ms/op
                 listUser·p0.999:  10.090 ms/op
                 listUser·p0.9999: 12.894 ms/op
                 listUser·p1.00:   13.402 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 320960
  mean =      2.988 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 94934 
    [ 2.500,  5.000) = 219768 
    [ 5.000,  7.500) = 5593 
    [ 7.500, 10.000) = 336 
    [10.000, 12.500) = 276 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      2.925 ms/op
     p(90.0000) =      3.850 ms/op
     p(95.0000) =      4.317 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     10.043 ms/op
     p(99.9900) =     16.742 ms/op
     p(99.9990) =     20.859 ms/op
     p(99.9999) =     21.037 ms/op
    p(100.0000) =     21.037 ms/op


# Run complete. Total time: 00:12:58

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.712 ± 0.565  ops/ms
ClientPb.existUser                       thrpt       3  13.088 ± 1.422  ops/ms
ClientPb.getUser                         thrpt       3  12.887 ± 2.056  ops/ms
ClientPb.listUser                        thrpt       3  10.687 ± 0.688  ops/ms
ClientPb.createUser                       avgt       3   2.538 ± 0.152   ms/op
ClientPb.existUser                        avgt       3   2.438 ± 0.255   ms/op
ClientPb.getUser                          avgt       3   2.480 ± 0.221   ms/op
ClientPb.listUser                         avgt       3   2.951 ± 0.218   ms/op
ClientPb.createUser                     sample  385438   2.488 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.969           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.548           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.142           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.808           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.621           ms/op
ClientPb.createUser:createUser·p0.9999  sample          12.763           ms/op
ClientPb.createUser:createUser·p1.00    sample          18.416           ms/op
ClientPb.existUser                      sample  396567   2.418 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.826           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.478           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.945           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.486           ms/op
ClientPb.existUser:existUser·p0.999     sample           7.081           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.971           ms/op
ClientPb.existUser:existUser·p1.00      sample          15.319           ms/op
ClientPb.getUser                        sample  388666   2.468 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.783           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.482           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.006           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.121           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.711           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.081           ms/op
ClientPb.getUser:getUser·p0.9999        sample          12.960           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.418           ms/op
ClientPb.listUser                       sample  320960   2.988 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.860           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.925           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.850           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.317           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.472           ms/op
ClientPb.listUser:listUser·p0.999       sample          10.043           ms/op
ClientPb.listUser:listUser·p0.9999      sample          16.742           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.037           ms/op
