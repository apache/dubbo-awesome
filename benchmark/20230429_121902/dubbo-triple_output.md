# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.235 ops/ms
# Warmup Iteration   2: 5.832 ops/ms
# Warmup Iteration   3: 8.440 ops/ms
Iteration   1: 9.256 ops/ms
Iteration   2: 9.421 ops/ms
Iteration   3: 9.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.343 ±(99.9%) 1.517 ops/ms [Average]
  (min, avg, max) = (9.256, 9.343, 9.421), stdev = 0.083
  CI (99.9%): [7.827, 10.860] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.547 ops/ms
# Warmup Iteration   2: 8.272 ops/ms
# Warmup Iteration   3: 10.025 ops/ms
Iteration   1: 10.164 ops/ms
Iteration   2: 10.001 ops/ms
Iteration   3: 9.937 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.034 ±(99.9%) 2.137 ops/ms [Average]
  (min, avg, max) = (9.937, 10.034, 10.164), stdev = 0.117
  CI (99.9%): [7.896, 12.171] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.972 ops/ms
# Warmup Iteration   2: 8.301 ops/ms
# Warmup Iteration   3: 9.107 ops/ms
Iteration   1: 9.586 ops/ms
Iteration   2: 9.462 ops/ms
Iteration   3: 9.384 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.477 ±(99.9%) 1.852 ops/ms [Average]
  (min, avg, max) = (9.384, 9.477, 9.586), stdev = 0.101
  CI (99.9%): [7.626, 11.329] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.874 ops/ms
# Warmup Iteration   2: 7.030 ops/ms
# Warmup Iteration   3: 7.804 ops/ms
Iteration   1: 7.886 ops/ms
Iteration   2: 8.235 ops/ms
Iteration   3: 8.259 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.126 ±(99.9%) 3.803 ops/ms [Average]
  (min, avg, max) = (7.886, 8.126, 8.259), stdev = 0.208
  CI (99.9%): [4.323, 11.930] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 11.102 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.894 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.008 ms/op
Iteration   1: 3.449 ±(99.9%) 0.005 ms/op
Iteration   2: 3.429 ±(99.9%) 0.006 ms/op
Iteration   3: 3.399 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.425 ±(99.9%) 0.464 ms/op [Average]
  (min, avg, max) = (3.399, 3.425, 3.449), stdev = 0.025
  CI (99.9%): [2.961, 3.889] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 8.743 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.523 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.005 ms/op
Iteration   1: 3.493 ±(99.9%) 0.005 ms/op
Iteration   2: 3.410 ±(99.9%) 0.006 ms/op
Iteration   3: 3.236 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.379 ±(99.9%) 2.391 ms/op [Average]
  (min, avg, max) = (3.236, 3.379, 3.493), stdev = 0.131
  CI (99.9%): [0.989, 5.770] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.558 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.671 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.488 ±(99.9%) 0.007 ms/op
Iteration   1: 3.488 ±(99.9%) 0.005 ms/op
Iteration   2: 3.288 ±(99.9%) 0.011 ms/op
Iteration   3: 3.523 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.433 ±(99.9%) 2.306 ms/op [Average]
  (min, avg, max) = (3.288, 3.433, 3.523), stdev = 0.126
  CI (99.9%): [1.127, 5.739] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.643 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.264 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.034 ±(99.9%) 0.008 ms/op
Iteration   1: 3.873 ±(99.9%) 0.013 ms/op
Iteration   2: 3.889 ±(99.9%) 0.010 ms/op
Iteration   3: 3.785 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.849 ±(99.9%) 1.020 ms/op [Average]
  (min, avg, max) = (3.785, 3.849, 3.889), stdev = 0.056
  CI (99.9%): [2.828, 4.869] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 9.790 ±(99.9%) 0.114 ms/op
# Warmup Iteration   2: 4.082 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.335 ±(99.9%) 0.010 ms/op
Iteration   1: 3.492 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.552 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   4.182 ms/op
                 createUser·p0.95:   4.956 ms/op
                 createUser·p0.99:   7.160 ms/op
                 createUser·p0.999:  18.142 ms/op
                 createUser·p0.9999: 22.342 ms/op
                 createUser·p1.00:   23.331 ms/op

Iteration   2: 3.371 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.505 ms/op
                 createUser·p0.50:   3.269 ms/op
                 createUser·p0.90:   3.854 ms/op
                 createUser·p0.95:   4.145 ms/op
                 createUser·p0.99:   5.669 ms/op
                 createUser·p0.999:  19.005 ms/op
                 createUser·p0.9999: 23.315 ms/op
                 createUser·p1.00:   23.921 ms/op

Iteration   3: 3.298 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.350 ms/op
                 createUser·p0.50:   3.178 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   5.456 ms/op
                 createUser·p0.999:  17.616 ms/op
                 createUser·p0.9999: 26.289 ms/op
                 createUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283649
  mean =      3.385 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9181 
    [ 2.500,  5.000) = 266660 
    [ 5.000,  7.500) = 6548 
    [ 7.500, 10.000) = 824 
    [10.000, 12.500) = 97 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 92 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 31 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      3.232 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.185 ms/op
     p(99.9000) =     17.804 ms/op
     p(99.9900) =     25.723 ms/op
     p(99.9990) =     26.810 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 8.582 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.562 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.228 ±(99.9%) 0.008 ms/op
Iteration   1: 3.321 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.337 ms/op
                 existUser·p0.50:   3.203 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   4.006 ms/op
                 existUser·p0.99:   6.226 ms/op
                 existUser·p0.999:  16.872 ms/op
                 existUser·p0.9999: 22.241 ms/op
                 existUser·p1.00:   22.774 ms/op

Iteration   2: 3.207 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.272 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  15.663 ms/op
                 existUser·p0.9999: 25.166 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   3: 3.419 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.565 ms/op
                 existUser·p0.50:   3.326 ms/op
                 existUser·p0.90:   4.014 ms/op
                 existUser·p0.95:   4.301 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  18.035 ms/op
                 existUser·p0.9999: 24.073 ms/op
                 existUser·p1.00:   25.002 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289479
  mean =      3.314 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12231 
    [ 2.500,  5.000) = 271728 
    [ 5.000,  7.500) = 4758 
    [ 7.500, 10.000) = 436 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 117 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.272 ms/op
     p(50.0000) =      3.240 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     16.796 ms/op
     p(99.9900) =     24.412 ms/op
     p(99.9990) =     25.573 ms/op
     p(99.9999) =     25.723 ms/op
    p(100.0000) =     25.723 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.437 ±(99.9%) 0.129 ms/op
# Warmup Iteration   2: 4.025 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.537 ±(99.9%) 0.011 ms/op
Iteration   1: 3.570 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.507 ms/op
                 getUser·p0.50:   3.420 ms/op
                 getUser·p0.90:   4.133 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  20.274 ms/op
                 getUser·p0.9999: 27.404 ms/op
                 getUser·p1.00:   28.279 ms/op

Iteration   2: 3.510 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.698 ms/op
                 getUser·p0.50:   3.342 ms/op
                 getUser·p0.90:   3.899 ms/op
                 getUser·p0.95:   4.964 ms/op
                 getUser·p0.99:   6.922 ms/op
                 getUser·p0.999:  22.509 ms/op
                 getUser·p0.9999: 26.214 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   3: 3.537 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.923 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.178 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   6.988 ms/op
                 getUser·p0.999:  21.955 ms/op
                 getUser·p0.9999: 27.032 ms/op
                 getUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270962
  mean =      3.539 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7435 
    [ 2.500,  5.000) = 253700 
    [ 5.000,  7.500) = 8137 
    [ 7.500, 10.000) = 1274 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 18 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 98 

  Percentiles, ms/op:
      p(0.0000) =      1.507 ms/op
     p(50.0000) =      3.375 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      6.726 ms/op
     p(99.9000) =     21.399 ms/op
     p(99.9900) =     26.932 ms/op
     p(99.9990) =     28.344 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.584 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.736 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.152 ±(99.9%) 0.012 ms/op
Iteration   1: 4.132 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.989 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.932 ms/op
                 listUser·p0.99:   8.039 ms/op
                 listUser·p0.999:  21.832 ms/op
                 listUser·p0.9999: 25.154 ms/op
                 listUser·p1.00:   26.313 ms/op

Iteration   2: 3.961 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.339 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.274 ms/op
                 listUser·p0.999:  16.307 ms/op
                 listUser·p0.9999: 19.825 ms/op
                 listUser·p1.00:   19.857 ms/op

Iteration   3: 3.939 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.154 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  14.137 ms/op
                 listUser·p0.9999: 15.039 ms/op
                 listUser·p1.00:   17.170 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 239248
  mean =      4.009 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25 
    [ 2.500,  5.000) = 230327 
    [ 5.000,  7.500) = 6333 
    [ 7.500, 10.000) = 1701 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 374 
    [15.000, 17.500) = 110 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 76 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.989 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.661 ms/op
     p(99.0000) =      7.651 ms/op
     p(99.9000) =     16.282 ms/op
     p(99.9900) =     23.507 ms/op
     p(99.9990) =     25.939 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.343 ± 1.517  ops/ms
ClientPb.existUser                       thrpt       3  10.034 ± 2.137  ops/ms
ClientPb.getUser                         thrpt       3   9.477 ± 1.852  ops/ms
ClientPb.listUser                        thrpt       3   8.126 ± 3.803  ops/ms
ClientPb.createUser                       avgt       3   3.425 ± 0.464   ms/op
ClientPb.existUser                        avgt       3   3.379 ± 2.391   ms/op
ClientPb.getUser                          avgt       3   3.433 ± 2.306   ms/op
ClientPb.listUser                         avgt       3   3.849 ± 1.020   ms/op
ClientPb.createUser                     sample  283649   3.385 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.350           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.232           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.185           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.804           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.723           ms/op
ClientPb.createUser:createUser·p1.00    sample          27.034           ms/op
ClientPb.existUser                      sample  289479   3.314 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.272           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.240           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.628           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.796           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.412           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.723           ms/op
ClientPb.getUser                        sample  270962   3.539 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.507           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.375           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.112           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.522           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.726           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.399           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.932           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.344           ms/op
ClientPb.listUser                       sample  239248   4.009 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.989           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.834           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.383           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.661           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.651           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.282           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.507           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.313           ms/op
