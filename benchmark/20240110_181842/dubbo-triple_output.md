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
# Warmup Iteration   1: 4.914 ops/ms
# Warmup Iteration   2: 12.121 ops/ms
# Warmup Iteration   3: 12.314 ops/ms
Iteration   1: 12.523 ops/ms
Iteration   2: 12.788 ops/ms
Iteration   3: 12.682 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.665 ±(99.9%) 2.438 ops/ms [Average]
  (min, avg, max) = (12.523, 12.665, 12.788), stdev = 0.134
  CI (99.9%): [10.227, 15.102] (assumes normal distribution)


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
# Warmup Iteration   1: 8.166 ops/ms
# Warmup Iteration   2: 13.028 ops/ms
# Warmup Iteration   3: 13.090 ops/ms
Iteration   1: 12.850 ops/ms
Iteration   2: 13.075 ops/ms
Iteration   3: 13.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.998 ±(99.9%) 2.343 ops/ms [Average]
  (min, avg, max) = (12.850, 12.998, 13.075), stdev = 0.128
  CI (99.9%): [10.656, 15.341] (assumes normal distribution)


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
# Warmup Iteration   1: 7.891 ops/ms
# Warmup Iteration   2: 12.673 ops/ms
# Warmup Iteration   3: 12.920 ops/ms
Iteration   1: 12.820 ops/ms
Iteration   2: 12.745 ops/ms
Iteration   3: 12.696 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.754 ±(99.9%) 1.139 ops/ms [Average]
  (min, avg, max) = (12.696, 12.754, 12.820), stdev = 0.062
  CI (99.9%): [11.615, 13.893] (assumes normal distribution)


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
# Warmup Iteration   1: 6.409 ops/ms
# Warmup Iteration   2: 10.448 ops/ms
# Warmup Iteration   3: 10.599 ops/ms
Iteration   1: 10.438 ops/ms
Iteration   2: 10.686 ops/ms
Iteration   3: 10.575 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.566 ±(99.9%) 2.268 ops/ms [Average]
  (min, avg, max) = (10.438, 10.566, 10.686), stdev = 0.124
  CI (99.9%): [8.298, 12.834] (assumes normal distribution)


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
# Warmup Iteration   1: 4.079 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.559 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.528 ±(99.9%) 0.004 ms/op
Iteration   1: 2.559 ±(99.9%) 0.004 ms/op
Iteration   2: 2.529 ±(99.9%) 0.004 ms/op
Iteration   3: 2.535 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.541 ±(99.9%) 0.287 ms/op [Average]
  (min, avg, max) = (2.529, 2.541, 2.559), stdev = 0.016
  CI (99.9%): [2.254, 2.828] (assumes normal distribution)


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
# Warmup Iteration   1: 3.764 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.435 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.442 ±(99.9%) 0.004 ms/op
Iteration   1: 2.423 ±(99.9%) 0.004 ms/op
Iteration   2: 2.412 ±(99.9%) 0.004 ms/op
Iteration   3: 2.420 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.418 ±(99.9%) 0.103 ms/op [Average]
  (min, avg, max) = (2.412, 2.418, 2.423), stdev = 0.006
  CI (99.9%): [2.315, 2.521] (assumes normal distribution)


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
# Warmup Iteration   1: 4.038 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 2.602 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.546 ±(99.9%) 0.004 ms/op
Iteration   1: 2.513 ±(99.9%) 0.003 ms/op
Iteration   2: 2.527 ±(99.9%) 0.005 ms/op
Iteration   3: 2.550 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.530 ±(99.9%) 0.335 ms/op [Average]
  (min, avg, max) = (2.513, 2.530, 2.550), stdev = 0.018
  CI (99.9%): [2.195, 2.866] (assumes normal distribution)


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
# Warmup Iteration   1: 4.644 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.050 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.004 ms/op
Iteration   1: 3.005 ±(99.9%) 0.005 ms/op
Iteration   2: 3.009 ±(99.9%) 0.005 ms/op
Iteration   3: 3.013 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.009 ±(99.9%) 0.068 ms/op [Average]
  (min, avg, max) = (3.005, 3.009, 3.013), stdev = 0.004
  CI (99.9%): [2.941, 3.077] (assumes normal distribution)


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
# Warmup Iteration   1: 4.088 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.696 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 2.535 ±(99.9%) 0.006 ms/op
Iteration   1: 2.524 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.965 ms/op
                 createUser·p0.50:   2.593 ms/op
                 createUser·p0.90:   3.060 ms/op
                 createUser·p0.95:   3.166 ms/op
                 createUser·p0.99:   3.690 ms/op
                 createUser·p0.999:  10.699 ms/op
                 createUser·p0.9999: 14.281 ms/op
                 createUser·p1.00:   14.877 ms/op

Iteration   2: 2.561 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.913 ms/op
                 createUser·p0.50:   2.634 ms/op
                 createUser·p0.90:   3.105 ms/op
                 createUser·p0.95:   3.236 ms/op
                 createUser·p0.99:   4.067 ms/op
                 createUser·p0.999:  9.421 ms/op
                 createUser·p0.9999: 11.866 ms/op
                 createUser·p1.00:   12.304 ms/op

Iteration   3: 2.531 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.999 ms/op
                 createUser·p0.50:   2.609 ms/op
                 createUser·p0.90:   3.068 ms/op
                 createUser·p0.95:   3.178 ms/op
                 createUser·p0.99:   3.707 ms/op
                 createUser·p0.999:  9.334 ms/op
                 createUser·p0.9999: 11.780 ms/op
                 createUser·p1.00:   16.155 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 377829
  mean =      2.538 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 181702 
    [ 2.500,  3.750) = 191819 
    [ 3.750,  5.000) = 3275 
    [ 5.000,  6.250) = 448 
    [ 6.250,  7.500) = 64 
    [ 7.500,  8.750) = 73 
    [ 8.750, 10.000) = 97 
    [10.000, 11.250) = 136 
    [11.250, 12.500) = 85 
    [12.500, 13.750) = 61 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.913 ms/op
     p(50.0000) =      2.609 ms/op
     p(90.0000) =      3.080 ms/op
     p(95.0000) =      3.191 ms/op
     p(99.0000) =      3.822 ms/op
     p(99.9000) =      9.358 ms/op
     p(99.9900) =     13.229 ms/op
     p(99.9990) =     14.753 ms/op
     p(99.9999) =     16.155 ms/op
    p(100.0000) =     16.155 ms/op


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
# Warmup Iteration   1: 3.724 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.472 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.449 ±(99.9%) 0.005 ms/op
Iteration   1: 2.448 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   2.957 ms/op
                 existUser·p0.95:   3.043 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  5.607 ms/op
                 existUser·p0.9999: 13.222 ms/op
                 existUser·p1.00:   14.139 ms/op

Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.924 ms/op
                 existUser·p0.50:   2.580 ms/op
                 existUser·p0.90:   2.986 ms/op
                 existUser·p0.95:   3.072 ms/op
                 existUser·p0.99:   3.543 ms/op
                 existUser·p0.999:  8.282 ms/op
                 existUser·p0.9999: 13.292 ms/op
                 existUser·p1.00:   14.123 ms/op

Iteration   3: 2.482 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.952 ms/op
                 existUser·p0.50:   2.560 ms/op
                 existUser·p0.90:   3.006 ms/op
                 existUser·p0.95:   3.117 ms/op
                 existUser·p0.99:   3.764 ms/op
                 existUser·p0.999:  9.301 ms/op
                 existUser·p0.9999: 11.930 ms/op
                 existUser·p1.00:   12.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 388704
  mean =      2.467 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 37 
    [ 1.250,  2.500) = 190377 
    [ 2.500,  3.750) = 195115 
    [ 3.750,  5.000) = 2394 
    [ 5.000,  6.250) = 343 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 133 
    [10.000, 11.250) = 82 
    [11.250, 12.500) = 96 
    [12.500, 13.750) = 89 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.924 ms/op
     p(50.0000) =      2.560 ms/op
     p(90.0000) =      2.982 ms/op
     p(95.0000) =      3.076 ms/op
     p(99.0000) =      3.612 ms/op
     p(99.9000) =      8.934 ms/op
     p(99.9900) =     13.156 ms/op
     p(99.9990) =     14.041 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 3.899 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 2.642 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.525 ±(99.9%) 0.005 ms/op
Iteration   1: 2.521 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   2.544 ms/op
                 getUser·p0.90:   3.068 ms/op
                 getUser·p0.95:   3.199 ms/op
                 getUser·p0.99:   3.953 ms/op
                 getUser·p0.999:  10.976 ms/op
                 getUser·p0.9999: 14.066 ms/op
                 getUser·p1.00:   14.664 ms/op

Iteration   2: 2.545 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.786 ms/op
                 getUser·p0.50:   2.601 ms/op
                 getUser·p0.90:   3.097 ms/op
                 getUser·p0.95:   3.241 ms/op
                 getUser·p0.99:   4.104 ms/op
                 getUser·p0.999:  8.844 ms/op
                 getUser·p0.9999: 12.282 ms/op
                 getUser·p1.00:   12.943 ms/op

Iteration   3: 2.527 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.002 ms/op
                 getUser·p0.50:   2.548 ms/op
                 getUser·p0.90:   3.088 ms/op
                 getUser·p0.95:   3.219 ms/op
                 getUser·p0.99:   3.883 ms/op
                 getUser·p0.999:  8.691 ms/op
                 getUser·p0.9999: 10.852 ms/op
                 getUser·p1.00:   11.403 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 378947
  mean =      2.531 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 184527 
    [ 2.500,  3.750) = 188962 
    [ 3.750,  5.000) = 4396 
    [ 5.000,  6.250) = 531 
    [ 6.250,  7.500) = 69 
    [ 7.500,  8.750) = 15 
    [ 8.750, 10.000) = 108 
    [10.000, 11.250) = 112 
    [11.250, 12.500) = 76 
    [12.500, 13.750) = 48 
    [13.750, 15.000) = 34 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.786 ms/op
     p(50.0000) =      2.564 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.219 ms/op
     p(99.0000) =      3.965 ms/op
     p(99.9000) =      8.750 ms/op
     p(99.9900) =     13.715 ms/op
     p(99.9990) =     14.582 ms/op
     p(99.9999) =     14.664 ms/op
    p(100.0000) =     14.664 ms/op


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
# Warmup Iteration   1: 4.570 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.123 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.082 ±(99.9%) 0.009 ms/op
Iteration   1: 3.054 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.807 ms/op
                 listUser·p0.50:   2.990 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.432 ms/op
                 listUser·p0.99:   5.644 ms/op
                 listUser·p0.999:  9.672 ms/op
                 listUser·p0.9999: 12.067 ms/op
                 listUser·p1.00:   12.763 ms/op

Iteration   2: 3.060 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.955 ms/op
                 listUser·p0.50:   3.002 ms/op
                 listUser·p0.90:   3.936 ms/op
                 listUser·p0.95:   4.448 ms/op
                 listUser·p0.99:   5.571 ms/op
                 listUser·p0.999:  9.004 ms/op
                 listUser·p0.9999: 10.995 ms/op
                 listUser·p1.00:   11.600 ms/op

Iteration   3: 3.404 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.037 ms/op
                 listUser·p0.50:   3.133 ms/op
                 listUser·p0.90:   4.719 ms/op
                 listUser·p0.95:   5.808 ms/op
                 listUser·p0.99:   9.121 ms/op
                 listUser·p0.999:  13.190 ms/op
                 listUser·p0.9999: 19.682 ms/op
                 listUser·p1.00:   21.332 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 303043
  mean =      3.165 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 74029 
    [ 2.500,  5.000) = 216403 
    [ 5.000,  7.500) = 10097 
    [ 7.500, 10.000) = 1759 
    [10.000, 12.500) = 589 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      4.149 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     11.338 ms/op
     p(99.9900) =     16.200 ms/op
     p(99.9990) =     21.035 ms/op
     p(99.9999) =     21.332 ms/op
    p(100.0000) =     21.332 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.665 ± 2.438  ops/ms
ClientPb.existUser                       thrpt       3  12.998 ± 2.343  ops/ms
ClientPb.getUser                         thrpt       3  12.754 ± 1.139  ops/ms
ClientPb.listUser                        thrpt       3  10.566 ± 2.268  ops/ms
ClientPb.createUser                       avgt       3   2.541 ± 0.287   ms/op
ClientPb.existUser                        avgt       3   2.418 ± 0.103   ms/op
ClientPb.getUser                          avgt       3   2.530 ± 0.335   ms/op
ClientPb.listUser                         avgt       3   3.009 ± 0.068   ms/op
ClientPb.createUser                     sample  377829   2.538 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.913           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.609           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.080           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.191           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.822           ms/op
ClientPb.createUser:createUser·p0.999   sample           9.358           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.229           ms/op
ClientPb.createUser:createUser·p1.00    sample          16.155           ms/op
ClientPb.existUser                      sample  388704   2.467 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.924           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.560           ms/op
ClientPb.existUser:existUser·p0.90      sample           2.982           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.612           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.934           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.156           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.139           ms/op
ClientPb.getUser                        sample  378947   2.531 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.786           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.564           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.084           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.219           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.999         sample           8.750           ms/op
ClientPb.getUser:getUser·p0.9999        sample          13.715           ms/op
ClientPb.getUser:getUser·p1.00          sample          14.664           ms/op
ClientPb.listUser                       sample  303043   3.165 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.807           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.039           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.149           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.817           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.094           ms/op
ClientPb.listUser:listUser·p0.999       sample          11.338           ms/op
ClientPb.listUser:listUser·p0.9999      sample          16.200           ms/op
ClientPb.listUser:listUser·p1.00        sample          21.332           ms/op
