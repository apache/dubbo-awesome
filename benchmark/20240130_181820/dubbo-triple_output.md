# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.061 ops/ms
# Warmup Iteration   2: 12.295 ops/ms
# Warmup Iteration   3: 12.649 ops/ms
Iteration   1: 12.836 ops/ms
Iteration   2: 12.886 ops/ms
Iteration   3: 12.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.888 ±(99.9%) 0.965 ops/ms [Average]
  (min, avg, max) = (12.836, 12.888, 12.941), stdev = 0.053
  CI (99.9%): [11.922, 13.853] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:11:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.224 ops/ms
# Warmup Iteration   2: 13.161 ops/ms
# Warmup Iteration   3: 13.234 ops/ms
Iteration   1: 13.214 ops/ms
Iteration   2: 13.330 ops/ms
Iteration   3: 13.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  13.208 ±(99.9%) 2.286 ops/ms [Average]
  (min, avg, max) = (13.080, 13.208, 13.330), stdev = 0.125
  CI (99.9%): [10.922, 15.493] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.090 ops/ms
# Warmup Iteration   2: 12.583 ops/ms
# Warmup Iteration   3: 12.888 ops/ms
Iteration   1: 12.971 ops/ms
Iteration   2: 13.103 ops/ms
Iteration   3: 12.929 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  13.001 ±(99.9%) 1.659 ops/ms [Average]
  (min, avg, max) = (12.929, 13.001, 13.103), stdev = 0.091
  CI (99.9%): [11.342, 14.660] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.910 ops/ms
# Warmup Iteration   2: 10.351 ops/ms
# Warmup Iteration   3: 10.629 ops/ms
Iteration   1: 10.713 ops/ms
Iteration   2: 10.675 ops/ms
Iteration   3: 10.676 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.688 ±(99.9%) 0.392 ops/ms [Average]
  (min, avg, max) = (10.675, 10.688, 10.713), stdev = 0.021
  CI (99.9%): [10.296, 11.080] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:39
# Fork: 1 of 1
# Warmup Iteration   1: 3.882 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.564 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.499 ±(99.9%) 0.004 ms/op
Iteration   1: 2.510 ±(99.9%) 0.004 ms/op
Iteration   2: 2.498 ±(99.9%) 0.003 ms/op
Iteration   3: 2.492 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.500 ±(99.9%) 0.172 ms/op [Average]
  (min, avg, max) = (2.492, 2.500, 2.510), stdev = 0.009
  CI (99.9%): [2.328, 2.672] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:34
# Fork: 1 of 1
# Warmup Iteration   1: 3.641 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.446 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.391 ±(99.9%) 0.003 ms/op
Iteration   1: 2.406 ±(99.9%) 0.004 ms/op
Iteration   2: 2.417 ±(99.9%) 0.004 ms/op
Iteration   3: 2.429 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.418 ±(99.9%) 0.209 ms/op [Average]
  (min, avg, max) = (2.406, 2.418, 2.429), stdev = 0.011
  CI (99.9%): [2.208, 2.627] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:29
# Fork: 1 of 1
# Warmup Iteration   1: 3.708 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.506 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.482 ±(99.9%) 0.004 ms/op
Iteration   1: 2.479 ±(99.9%) 0.005 ms/op
Iteration   2: 2.458 ±(99.9%) 0.004 ms/op
Iteration   3: 2.459 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.465 ±(99.9%) 0.219 ms/op [Average]
  (min, avg, max) = (2.458, 2.465, 2.479), stdev = 0.012
  CI (99.9%): [2.246, 2.684] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:24
# Fork: 1 of 1
# Warmup Iteration   1: 4.650 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.064 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.006 ms/op
Iteration   1: 3.062 ±(99.9%) 0.006 ms/op
Iteration   2: 3.038 ±(99.9%) 0.007 ms/op
Iteration   3: 3.029 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.043 ±(99.9%) 0.308 ms/op [Average]
  (min, avg, max) = (3.029, 3.043, 3.062), stdev = 0.017
  CI (99.9%): [2.735, 3.351] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.183 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.611 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.491 ±(99.9%) 0.006 ms/op
Iteration   1: 2.492 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.862 ms/op
                 createUser·p0.50:   2.531 ms/op
                 createUser·p0.90:   3.035 ms/op
                 createUser·p0.95:   3.158 ms/op
                 createUser·p0.99:   3.686 ms/op
                 createUser·p0.999:  11.874 ms/op
                 createUser·p0.9999: 13.651 ms/op
                 createUser·p1.00:   14.074 ms/op

Iteration   2: 2.462 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.976 ms/op
                 createUser·p0.50:   2.503 ms/op
                 createUser·p0.90:   3.002 ms/op
                 createUser·p0.95:   3.121 ms/op
                 createUser·p0.99:   3.600 ms/op
                 createUser·p0.999:  6.307 ms/op
                 createUser·p0.9999: 12.665 ms/op
                 createUser·p1.00:   13.500 ms/op

Iteration   3: 2.491 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   2.540 ms/op
                 createUser·p0.90:   3.031 ms/op
                 createUser·p0.95:   3.162 ms/op
                 createUser·p0.99:   3.793 ms/op
                 createUser·p0.999:  8.017 ms/op
                 createUser·p0.9999: 10.898 ms/op
                 createUser·p1.00:   12.665 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 386436
  mean =      2.482 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 50 
    [ 1.250,  2.500) = 190847 
    [ 2.500,  3.750) = 192031 
    [ 3.750,  5.000) = 2867 
    [ 5.000,  6.250) = 215 
    [ 6.250,  7.500) = 9 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 102 
    [10.000, 11.250) = 89 
    [11.250, 12.500) = 87 
    [12.500, 13.750) = 102 
    [13.750, 15.000) = 11 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.862 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.023 ms/op
     p(95.0000) =      3.150 ms/op
     p(99.0000) =      3.707 ms/op
     p(99.9000) =      8.798 ms/op
     p(99.9900) =     13.304 ms/op
     p(99.9990) =     14.041 ms/op
     p(99.9999) =     14.074 ms/op
    p(100.0000) =     14.074 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.531 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 2.426 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.423 ±(99.9%) 0.005 ms/op
Iteration   1: 2.419 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.925 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.424 ms/op
                 existUser·p0.999:  6.423 ms/op
                 existUser·p0.9999: 13.206 ms/op
                 existUser·p1.00:   13.648 ms/op

Iteration   2: 2.422 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.857 ms/op
                 existUser·p0.50:   2.499 ms/op
                 existUser·p0.90:   2.937 ms/op
                 existUser·p0.95:   3.039 ms/op
                 existUser·p0.99:   3.541 ms/op
                 existUser·p0.999:  7.418 ms/op
                 existUser·p0.9999: 12.475 ms/op
                 existUser·p1.00:   13.009 ms/op

Iteration   3: 2.434 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.977 ms/op
                 existUser·p0.50:   2.478 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.076 ms/op
                 existUser·p0.99:   3.797 ms/op
                 existUser·p0.999:  8.829 ms/op
                 existUser·p0.9999: 11.933 ms/op
                 existUser·p1.00:   13.648 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 395467
  mean =      2.425 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 33 
    [ 1.250,  2.500) = 197389 
    [ 2.500,  3.750) = 195067 
    [ 3.750,  5.000) = 2194 
    [ 5.000,  6.250) = 210 
    [ 6.250,  7.500) = 99 
    [ 7.500,  8.750) = 110 
    [ 8.750, 10.000) = 107 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 127 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      2.503 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      3.596 ms/op
     p(99.9000) =      8.480 ms/op
     p(99.9900) =     12.771 ms/op
     p(99.9990) =     13.617 ms/op
     p(99.9999) =     13.648 ms/op
    p(100.0000) =     13.648 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.787 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 2.549 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.498 ±(99.9%) 0.006 ms/op
Iteration   1: 2.481 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.959 ms/op
                 getUser·p0.50:   2.507 ms/op
                 getUser·p0.90:   3.019 ms/op
                 getUser·p0.95:   3.138 ms/op
                 getUser·p0.99:   3.777 ms/op
                 getUser·p0.999:  6.218 ms/op
                 getUser·p0.9999: 13.959 ms/op
                 getUser·p1.00:   14.500 ms/op

Iteration   2: 2.490 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.970 ms/op
                 getUser·p0.50:   2.499 ms/op
                 getUser·p0.90:   3.023 ms/op
                 getUser·p0.95:   3.150 ms/op
                 getUser·p0.99:   3.928 ms/op
                 getUser·p0.999:  8.182 ms/op
                 getUser·p0.9999: 13.763 ms/op
                 getUser·p1.00:   13.943 ms/op

Iteration   3: 2.466 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.849 ms/op
                 getUser·p0.50:   2.482 ms/op
                 getUser·p0.90:   3.002 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   3.707 ms/op
                 getUser·p0.999:  7.455 ms/op
                 getUser·p0.9999: 12.632 ms/op
                 getUser·p1.00:   13.681 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 386927
  mean =      2.479 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 90 
    [ 1.250,  2.500) = 193883 
    [ 2.500,  3.750) = 188778 
    [ 3.750,  5.000) = 3173 
    [ 5.000,  6.250) = 525 
    [ 6.250,  7.500) = 119 
    [ 7.500,  8.750) = 25 
    [ 8.750, 10.000) = 85 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 121 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.849 ms/op
     p(50.0000) =      2.494 ms/op
     p(90.0000) =      3.015 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.797 ms/op
     p(99.9000) =      7.119 ms/op
     p(99.9900) =     13.470 ms/op
     p(99.9990) =     14.150 ms/op
     p(99.9999) =     14.500 ms/op
    p(100.0000) =     14.500 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.792 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.009 ms/op
Iteration   1: 3.052 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.881 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.990 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   5.734 ms/op
                 listUser·p0.999:  9.552 ms/op
                 listUser·p0.9999: 10.896 ms/op
                 listUser·p1.00:   11.567 ms/op

Iteration   2: 3.017 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.939 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.895 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.421 ms/op
                 listUser·p0.9999: 13.353 ms/op
                 listUser·p1.00:   13.992 ms/op

Iteration   3: 3.015 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.761 ms/op
                 listUser·p0.50:   2.953 ms/op
                 listUser·p0.90:   3.887 ms/op
                 listUser·p0.95:   4.391 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  9.436 ms/op
                 listUser·p0.9999: 10.974 ms/op
                 listUser·p1.00:   12.927 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 316784
  mean =      3.028 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 132 
    [ 1.250,  2.500) = 90625 
    [ 2.500,  3.750) = 185074 
    [ 3.750,  5.000) = 33312 
    [ 5.000,  6.250) = 6153 
    [ 6.250,  7.500) = 807 
    [ 7.500,  8.750) = 266 
    [ 8.750, 10.000) = 209 
    [10.000, 11.250) = 180 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 15 
    [13.750, 15.000) = 3 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.761 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =      9.437 ms/op
     p(99.9900) =     11.048 ms/op
     p(99.9990) =     13.915 ms/op
     p(99.9999) =     13.992 ms/op
    p(100.0000) =     13.992 ms/op


# Run complete. Total time: 00:13:00

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.888 ± 0.965  ops/ms
ClientPb.existUser                       thrpt       3  13.208 ± 2.286  ops/ms
ClientPb.getUser                         thrpt       3  13.001 ± 1.659  ops/ms
ClientPb.listUser                        thrpt       3  10.688 ± 0.392  ops/ms
ClientPb.createUser                       avgt       3   2.500 ± 0.172   ms/op
ClientPb.existUser                        avgt       3   2.418 ± 0.209   ms/op
ClientPb.getUser                          avgt       3   2.465 ± 0.219   ms/op
ClientPb.listUser                         avgt       3   3.043 ± 0.308   ms/op
ClientPb.createUser                     sample  386436   2.482 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.862           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.523           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.023           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.150           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.707           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.798           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.304           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.074           ms/op
ClientPb.existUser                      sample  395467   2.425 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.857           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.503           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.941           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.039           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.596           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.480           ms/op
ClientPb.existUser:existUser·p0.9999    sample          12.771           ms/op
ClientPb.existUser:existUser·p1.00      sample          13.648           ms/op
ClientPb.getUser                        sample  386927   2.479 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.849           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.494           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.015           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.133           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.797           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.119           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.470           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.500           ms/op
ClientPb.listUser                       sample  316784   3.028 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.761           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.966           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.636           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.437           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.048           ms/op
ClientPb.listUser:listUser·p1.00        sample          13.992           ms/op
