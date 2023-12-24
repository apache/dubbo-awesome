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
# Warmup Iteration   1: 4.757 ops/ms
# Warmup Iteration   2: 11.527 ops/ms
# Warmup Iteration   3: 11.990 ops/ms
Iteration   1: 12.275 ops/ms
Iteration   2: 12.151 ops/ms
Iteration   3: 12.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  12.248 ±(99.9%) 1.568 ops/ms [Average]
  (min, avg, max) = (12.151, 12.248, 12.317), stdev = 0.086
  CI (99.9%): [10.680, 13.816] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:53
# Fork: 1 of 1
# Warmup Iteration   1: 7.862 ops/ms
# Warmup Iteration   2: 12.884 ops/ms
# Warmup Iteration   3: 12.809 ops/ms
Iteration   1: 12.793 ops/ms
Iteration   2: 12.739 ops/ms
Iteration   3: 12.699 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  12.744 ±(99.9%) 0.864 ops/ms [Average]
  (min, avg, max) = (12.699, 12.744, 12.793), stdev = 0.047
  CI (99.9%): [11.879, 13.608] (assumes normal distribution)


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
# Warmup Iteration   1: 7.150 ops/ms
# Warmup Iteration   2: 12.414 ops/ms
# Warmup Iteration   3: 12.642 ops/ms
Iteration   1: 12.729 ops/ms
Iteration   2: 12.727 ops/ms
Iteration   3: 12.769 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  12.742 ±(99.9%) 0.430 ops/ms [Average]
  (min, avg, max) = (12.727, 12.742, 12.769), stdev = 0.024
  CI (99.9%): [12.312, 13.171] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 6.619 ops/ms
# Warmup Iteration   2: 10.356 ops/ms
# Warmup Iteration   3: 10.712 ops/ms
Iteration   1: 10.656 ops/ms
Iteration   2: 10.678 ops/ms
Iteration   3: 10.560 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  10.631 ±(99.9%) 1.139 ops/ms [Average]
  (min, avg, max) = (10.560, 10.631, 10.678), stdev = 0.062
  CI (99.9%): [9.492, 11.771] (assumes normal distribution)


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
# Warmup Iteration   1: 4.228 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.620 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.520 ±(99.9%) 0.004 ms/op
Iteration   1: 2.555 ±(99.9%) 0.004 ms/op
Iteration   2: 2.561 ±(99.9%) 0.003 ms/op
Iteration   3: 2.578 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  2.565 ±(99.9%) 0.212 ms/op [Average]
  (min, avg, max) = (2.555, 2.565, 2.578), stdev = 0.012
  CI (99.9%): [2.352, 2.777] (assumes normal distribution)


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
# Warmup Iteration   1: 3.917 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 2.507 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.531 ±(99.9%) 0.004 ms/op
Iteration   1: 2.491 ±(99.9%) 0.003 ms/op
Iteration   2: 2.517 ±(99.9%) 0.004 ms/op
Iteration   3: 2.537 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  2.515 ±(99.9%) 0.421 ms/op [Average]
  (min, avg, max) = (2.491, 2.515, 2.537), stdev = 0.023
  CI (99.9%): [2.094, 2.936] (assumes normal distribution)


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
# Warmup Iteration   1: 4.324 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 2.645 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.573 ±(99.9%) 0.004 ms/op
Iteration   1: 2.542 ±(99.9%) 0.005 ms/op
Iteration   2: 2.580 ±(99.9%) 0.005 ms/op
Iteration   3: 2.527 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  2.550 ±(99.9%) 0.504 ms/op [Average]
  (min, avg, max) = (2.527, 2.550, 2.580), stdev = 0.028
  CI (99.9%): [2.046, 3.054] (assumes normal distribution)


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
# Warmup Iteration   1: 4.746 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.072 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.022 ±(99.9%) 0.006 ms/op
Iteration   1: 3.014 ±(99.9%) 0.005 ms/op
Iteration   2: 3.006 ±(99.9%) 0.006 ms/op
Iteration   3: 3.013 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.011 ±(99.9%) 0.085 ms/op [Average]
  (min, avg, max) = (3.006, 3.011, 3.014), stdev = 0.005
  CI (99.9%): [2.926, 3.095] (assumes normal distribution)


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
# Warmup Iteration   1: 4.191 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.713 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.556 ±(99.9%) 0.006 ms/op
Iteration   1: 2.542 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.877 ms/op
                 createUser·p0.50:   2.621 ms/op
                 createUser·p0.90:   3.080 ms/op
                 createUser·p0.95:   3.199 ms/op
                 createUser·p0.99:   3.670 ms/op
                 createUser·p0.999:  11.731 ms/op
                 createUser·p0.9999: 13.753 ms/op
                 createUser·p1.00:   14.156 ms/op

Iteration   2: 2.534 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.064 ms/op
                 createUser·p0.95:   3.154 ms/op
                 createUser·p0.99:   3.498 ms/op
                 createUser·p0.999:  9.844 ms/op
                 createUser·p0.9999: 12.452 ms/op
                 createUser·p1.00:   12.976 ms/op

Iteration   3: 2.574 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.749 ms/op
                 createUser·p0.50:   2.642 ms/op
                 createUser·p0.90:   3.129 ms/op
                 createUser·p0.95:   3.273 ms/op
                 createUser·p0.99:   3.953 ms/op
                 createUser·p0.999:  8.227 ms/op
                 createUser·p0.9999: 12.977 ms/op
                 createUser·p1.00:   13.779 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 376199
  mean =      2.550 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 26 
    [ 1.250,  2.500) = 179015 
    [ 2.500,  3.750) = 193543 
    [ 3.750,  5.000) = 2881 
    [ 5.000,  6.250) = 295 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 92 
    [10.000, 11.250) = 64 
    [11.250, 12.500) = 105 
    [12.500, 13.750) = 98 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.749 ms/op
     p(50.0000) =      2.634 ms/op
     p(90.0000) =      3.088 ms/op
     p(95.0000) =      3.203 ms/op
     p(99.0000) =      3.731 ms/op
     p(99.9000) =      8.395 ms/op
     p(99.9900) =     13.271 ms/op
     p(99.9990) =     13.909 ms/op
     p(99.9999) =     14.156 ms/op
    p(100.0000) =     14.156 ms/op


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
# Warmup Iteration   1: 3.762 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 2.471 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.464 ±(99.9%) 0.005 ms/op
Iteration   1: 2.469 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.884 ms/op
                 existUser·p0.50:   2.540 ms/op
                 existUser·p0.90:   2.998 ms/op
                 existUser·p0.95:   3.097 ms/op
                 existUser·p0.99:   3.453 ms/op
                 existUser·p0.999:  6.921 ms/op
                 existUser·p0.9999: 13.947 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   2: 2.498 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.853 ms/op
                 existUser·p0.50:   2.544 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.682 ms/op
                 existUser·p0.999:  8.405 ms/op
                 existUser·p0.9999: 13.713 ms/op
                 existUser·p1.00:   14.385 ms/op

Iteration   3: 2.509 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.766 ms/op
                 existUser·p0.50:   2.585 ms/op
                 existUser·p0.90:   3.039 ms/op
                 existUser·p0.95:   3.154 ms/op
                 existUser·p0.99:   3.990 ms/op
                 existUser·p0.999:  8.349 ms/op
                 existUser·p0.9999: 11.883 ms/op
                 existUser·p1.00:   14.189 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 384876
  mean =      2.492 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 48 
    [ 1.250,  2.500) = 188424 
    [ 2.500,  3.750) = 192921 
    [ 3.750,  5.000) = 2516 
    [ 5.000,  6.250) = 421 
    [ 6.250,  7.500) = 122 
    [ 7.500,  8.750) = 84 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 98 
    [12.500, 13.750) = 79 
    [13.750, 15.000) = 27 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.766 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.133 ms/op
     p(99.0000) =      3.682 ms/op
     p(99.9000) =      8.341 ms/op
     p(99.9900) =     13.435 ms/op
     p(99.9990) =     14.369 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.218 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 2.632 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.545 ±(99.9%) 0.006 ms/op
Iteration   1: 2.518 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   2.568 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   3.686 ms/op
                 getUser·p0.999:  11.928 ms/op
                 getUser·p0.9999: 14.505 ms/op
                 getUser·p1.00:   15.663 ms/op

Iteration   2: 2.520 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   1.065 ms/op
                 getUser·p0.50:   2.556 ms/op
                 getUser·p0.90:   3.072 ms/op
                 getUser·p0.95:   3.191 ms/op
                 getUser·p0.99:   3.719 ms/op
                 getUser·p0.999:  9.753 ms/op
                 getUser·p0.9999: 14.472 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   3: 2.517 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.622 ms/op
                 getUser·p0.50:   2.552 ms/op
                 getUser·p0.90:   3.060 ms/op
                 getUser·p0.95:   3.187 ms/op
                 getUser·p0.99:   3.928 ms/op
                 getUser·p0.999:  7.537 ms/op
                 getUser·p0.9999: 11.216 ms/op
                 getUser·p1.00:   11.567 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 380909
  mean =      2.518 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 66 
    [ 1.250,  2.500) = 186835 
    [ 2.500,  3.750) = 190086 
    [ 3.750,  5.000) = 3105 
    [ 5.000,  6.250) = 384 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 37 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 70 
    [11.250, 12.500) = 59 
    [12.500, 13.750) = 99 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.622 ms/op
     p(50.0000) =      2.556 ms/op
     p(90.0000) =      3.064 ms/op
     p(95.0000) =      3.178 ms/op
     p(99.0000) =      3.764 ms/op
     p(99.9000) =      7.777 ms/op
     p(99.9900) =     14.333 ms/op
     p(99.9990) =     15.269 ms/op
     p(99.9999) =     15.663 ms/op
    p(100.0000) =     15.663 ms/op


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
# Warmup Iteration   1: 4.588 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.009 ms/op
Iteration   1: 3.046 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.966 ms/op
                 listUser·p0.50:   2.986 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.366 ms/op
                 listUser·p0.99:   5.595 ms/op
                 listUser·p0.999:  9.535 ms/op
                 listUser·p0.9999: 11.133 ms/op
                 listUser·p1.00:   11.583 ms/op

Iteration   2: 3.029 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.778 ms/op
                 listUser·p0.50:   2.974 ms/op
                 listUser·p0.90:   3.899 ms/op
                 listUser·p0.95:   4.399 ms/op
                 listUser·p0.99:   5.538 ms/op
                 listUser·p0.999:  9.379 ms/op
                 listUser·p0.9999: 11.148 ms/op
                 listUser·p1.00:   11.649 ms/op

Iteration   3: 3.057 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.791 ms/op
                 listUser·p0.50:   3.006 ms/op
                 listUser·p0.90:   3.965 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  9.961 ms/op
                 listUser·p0.9999: 10.971 ms/op
                 listUser·p1.00:   11.469 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 315056
  mean =      3.044 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 114 
    [ 1.250,  2.500) = 86410 
    [ 2.500,  3.750) = 186971 
    [ 3.750,  5.000) = 34187 
    [ 5.000,  6.250) = 6003 
    [ 6.250,  7.500) = 700 
    [ 7.500,  8.750) = 148 
    [ 8.750, 10.000) = 286 
    [10.000, 11.250) = 218 
    [11.250, 12.500) = 19 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.778 ms/op
     p(50.0000) =      2.990 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.603 ms/op
     p(99.9000) =      9.634 ms/op
     p(99.9900) =     11.076 ms/op
     p(99.9990) =     11.581 ms/op
     p(99.9999) =     11.649 ms/op
    p(100.0000) =     11.649 ms/op


# Run complete. Total time: 00:12:59

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3  12.248 ± 1.568  ops/ms
ClientPb.existUser                       thrpt       3  12.744 ± 0.864  ops/ms
ClientPb.getUser                         thrpt       3  12.742 ± 0.430  ops/ms
ClientPb.listUser                        thrpt       3  10.631 ± 1.139  ops/ms
ClientPb.createUser                       avgt       3   2.565 ± 0.212   ms/op
ClientPb.existUser                        avgt       3   2.515 ± 0.421   ms/op
ClientPb.getUser                          avgt       3   2.550 ± 0.504   ms/op
ClientPb.listUser                         avgt       3   3.011 ± 0.085   ms/op
ClientPb.createUser                     sample  376199   2.550 ± 0.003   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.749           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.634           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.088           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.203           ms/op
ClientPb.createUser:createUser·p0.99    sample           3.731           ms/op
ClientPb.createUser:createUser·p0.999   sample           8.395           ms/op
ClientPb.createUser:createUser·p0.9999  sample          13.271           ms/op
ClientPb.createUser:createUser·p1.00    sample          14.156           ms/op
ClientPb.existUser                      sample  384876   2.492 ± 0.003   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.766           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.556           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.027           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.133           ms/op
ClientPb.existUser:existUser·p0.99      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.999     sample           8.341           ms/op
ClientPb.existUser:existUser·p0.9999    sample          13.435           ms/op
ClientPb.existUser:existUser·p1.00      sample          14.418           ms/op
ClientPb.getUser                        sample  380909   2.518 ± 0.003   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.622           ms/op
ClientPb.getUser:getUser·p0.50          sample           2.556           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.064           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.178           ms/op
ClientPb.getUser:getUser·p0.99          sample           3.764           ms/op
ClientPb.getUser:getUser·p0.999         sample           7.777           ms/op
ClientPb.getUser:getUser·p0.9999        sample          14.333           ms/op
ClientPb.getUser:getUser·p1.00          sample          15.663           ms/op
ClientPb.listUser                       sample  315056   3.044 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.778           ms/op
ClientPb.listUser:listUser·p0.50        sample           2.990           ms/op
ClientPb.listUser:listUser·p0.90        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.407           ms/op
ClientPb.listUser:listUser·p0.99        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.999       sample           9.634           ms/op
ClientPb.listUser:listUser·p0.9999      sample          11.076           ms/op
ClientPb.listUser:listUser·p1.00        sample          11.649           ms/op
