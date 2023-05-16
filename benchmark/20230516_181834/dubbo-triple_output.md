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
# Warmup Iteration   1: 2.421 ops/ms
# Warmup Iteration   2: 5.836 ops/ms
# Warmup Iteration   3: 9.249 ops/ms
Iteration   1: 9.444 ops/ms
Iteration   2: 9.592 ops/ms
Iteration   3: 9.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.512 ±(99.9%) 1.366 ops/ms [Average]
  (min, avg, max) = (9.444, 9.512, 9.592), stdev = 0.075
  CI (99.9%): [8.146, 10.878] (assumes normal distribution)


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
# Warmup Iteration   1: 3.516 ops/ms
# Warmup Iteration   2: 9.047 ops/ms
# Warmup Iteration   3: 9.983 ops/ms
Iteration   1: 10.135 ops/ms
Iteration   2: 10.111 ops/ms
Iteration   3: 9.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.060 ±(99.9%) 2.019 ops/ms [Average]
  (min, avg, max) = (9.933, 10.060, 10.135), stdev = 0.111
  CI (99.9%): [8.041, 12.078] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.624 ops/ms
# Warmup Iteration   2: 9.444 ops/ms
# Warmup Iteration   3: 9.397 ops/ms
Iteration   1: 9.751 ops/ms
Iteration   2: 9.945 ops/ms
Iteration   3: 10.038 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.911 ±(99.9%) 2.675 ops/ms [Average]
  (min, avg, max) = (9.751, 9.911, 10.038), stdev = 0.147
  CI (99.9%): [7.236, 12.586] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.243 ops/ms
# Warmup Iteration   2: 7.544 ops/ms
# Warmup Iteration   3: 8.257 ops/ms
Iteration   1: 8.553 ops/ms
Iteration   2: 8.417 ops/ms
Iteration   3: 8.718 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.563 ±(99.9%) 2.753 ops/ms [Average]
  (min, avg, max) = (8.417, 8.563, 8.718), stdev = 0.151
  CI (99.9%): [5.809, 11.316] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.574 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 3.745 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.312 ±(99.9%) 0.007 ms/op
Iteration   1: 3.254 ±(99.9%) 0.007 ms/op
Iteration   2: 3.206 ±(99.9%) 0.003 ms/op
Iteration   3: 3.319 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.259 ±(99.9%) 1.031 ms/op [Average]
  (min, avg, max) = (3.206, 3.259, 3.319), stdev = 0.057
  CI (99.9%): [2.228, 4.291] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.098 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.470 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.009 ms/op
Iteration   1: 3.047 ±(99.9%) 0.004 ms/op
Iteration   2: 2.979 ±(99.9%) 0.006 ms/op
Iteration   3: 3.080 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.035 ±(99.9%) 0.936 ms/op [Average]
  (min, avg, max) = (2.979, 3.035, 3.080), stdev = 0.051
  CI (99.9%): [2.099, 3.971] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.790 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.489 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.473 ±(99.9%) 0.004 ms/op
Iteration   1: 3.164 ±(99.9%) 0.002 ms/op
Iteration   2: 3.271 ±(99.9%) 0.007 ms/op
Iteration   3: 3.247 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.227 ±(99.9%) 1.021 ms/op [Average]
  (min, avg, max) = (3.164, 3.227, 3.271), stdev = 0.056
  CI (99.9%): [2.206, 4.248] (assumes normal distribution)


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
# Warmup Iteration   1: 9.326 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.135 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.897 ±(99.9%) 0.005 ms/op
Iteration   1: 3.822 ±(99.9%) 0.003 ms/op
Iteration   2: 3.777 ±(99.9%) 0.007 ms/op
Iteration   3: 3.807 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.802 ±(99.9%) 0.424 ms/op [Average]
  (min, avg, max) = (3.777, 3.802, 3.822), stdev = 0.023
  CI (99.9%): [3.378, 4.226] (assumes normal distribution)


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
# Warmup Iteration   1: 7.563 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.591 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.128 ±(99.9%) 0.007 ms/op
Iteration   1: 3.094 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.374 ms/op
                 createUser·p0.50:   2.994 ms/op
                 createUser·p0.90:   3.187 ms/op
                 createUser·p0.95:   3.574 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  16.876 ms/op
                 createUser·p0.9999: 20.108 ms/op
                 createUser·p1.00:   20.742 ms/op

Iteration   2: 3.318 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.859 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   4.088 ms/op
                 createUser·p0.99:   5.513 ms/op
                 createUser·p0.999:  16.618 ms/op
                 createUser·p0.9999: 20.958 ms/op
                 createUser·p1.00:   21.758 ms/op

Iteration   3: 3.166 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.235 ms/op
                 createUser·p0.50:   3.170 ms/op
                 createUser·p0.90:   3.412 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   5.259 ms/op
                 createUser·p0.999:  12.026 ms/op
                 createUser·p0.9999: 18.055 ms/op
                 createUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 300767
  mean =      3.190 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18764 
    [ 2.500,  5.000) = 276203 
    [ 5.000,  7.500) = 4917 
    [ 7.500, 10.000) = 387 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 137 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.859 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      5.456 ms/op
     p(99.9000) =     16.155 ms/op
     p(99.9900) =     20.087 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


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
# Warmup Iteration   1: 7.346 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 3.408 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.030 ±(99.9%) 0.007 ms/op
Iteration   1: 3.181 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.112 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.338 ms/op
                 existUser·p0.95:   3.887 ms/op
                 existUser·p0.99:   6.019 ms/op
                 existUser·p0.999:  16.111 ms/op
                 existUser·p0.9999: 23.517 ms/op
                 existUser·p1.00:   25.002 ms/op

Iteration   2: 3.107 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.235 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   5.169 ms/op
                 existUser·p0.999:  9.455 ms/op
                 existUser·p0.9999: 21.855 ms/op
                 existUser·p1.00:   22.741 ms/op

Iteration   3: 3.174 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.292 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.396 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  11.190 ms/op
                 existUser·p0.9999: 23.097 ms/op
                 existUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 304195
  mean =      3.154 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27832 
    [ 2.500,  5.000) = 270830 
    [ 5.000,  7.500) = 4662 
    [ 7.500, 10.000) = 429 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 89 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 37 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.112 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.379 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      5.505 ms/op
     p(99.9000) =     11.453 ms/op
     p(99.9900) =     22.962 ms/op
     p(99.9990) =     24.016 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.797 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 3.629 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.269 ±(99.9%) 0.009 ms/op
Iteration   1: 3.422 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.665 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   4.071 ms/op
                 getUser·p0.95:   4.817 ms/op
                 getUser·p0.99:   6.357 ms/op
                 getUser·p0.999:  19.431 ms/op
                 getUser·p0.9999: 23.702 ms/op
                 getUser·p1.00:   24.805 ms/op

Iteration   2: 3.370 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.294 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.813 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   5.997 ms/op
                 getUser·p0.999:  20.387 ms/op
                 getUser·p0.9999: 28.689 ms/op
                 getUser·p1.00:   29.884 ms/op

Iteration   3: 3.214 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   1.440 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.699 ms/op
                 getUser·p0.99:   5.489 ms/op
                 getUser·p0.999:  10.486 ms/op
                 getUser·p0.9999: 22.192 ms/op
                 getUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 287737
  mean =      3.333 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16267 
    [ 2.500,  5.000) = 262648 
    [ 5.000,  7.500) = 7921 
    [ 7.500, 10.000) = 434 
    [10.000, 12.500) = 82 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 77 
    [20.000, 22.500) = 130 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.294 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.301 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     18.424 ms/op
     p(99.9900) =     27.933 ms/op
     p(99.9990) =     29.765 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.412 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.063 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.882 ±(99.9%) 0.013 ms/op
Iteration   1: 3.750 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.847 ms/op
                 listUser·p0.50:   3.555 ms/op
                 listUser·p0.90:   4.129 ms/op
                 listUser·p0.95:   4.415 ms/op
                 listUser·p0.99:   7.381 ms/op
                 listUser·p0.999:  14.757 ms/op
                 listUser·p0.9999: 22.329 ms/op
                 listUser·p1.00:   23.790 ms/op

Iteration   2: 3.742 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.273 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   4.116 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  12.477 ms/op
                 listUser·p0.9999: 14.883 ms/op
                 listUser·p1.00:   15.450 ms/op

Iteration   3: 3.735 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.739 ms/op
                 listUser·p0.50:   3.613 ms/op
                 listUser·p0.90:   4.002 ms/op
                 listUser·p0.95:   4.194 ms/op
                 listUser·p0.99:   7.152 ms/op
                 listUser·p0.999:  14.205 ms/op
                 listUser·p0.9999: 18.711 ms/op
                 listUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256354
  mean =      3.743 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 75 
    [ 2.500,  5.000) = 247837 
    [ 5.000,  7.500) = 6289 
    [ 7.500, 10.000) = 1463 
    [10.000, 12.500) = 312 
    [12.500, 15.000) = 207 
    [15.000, 17.500) = 96 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.739 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.084 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      7.234 ms/op
     p(99.9000) =     13.664 ms/op
     p(99.9900) =     21.299 ms/op
     p(99.9990) =     23.525 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.512 ± 1.366  ops/ms
ClientPb.existUser                       thrpt       3  10.060 ± 2.019  ops/ms
ClientPb.getUser                         thrpt       3   9.911 ± 2.675  ops/ms
ClientPb.listUser                        thrpt       3   8.563 ± 2.753  ops/ms
ClientPb.createUser                       avgt       3   3.259 ± 1.031   ms/op
ClientPb.existUser                        avgt       3   3.035 ± 0.936   ms/op
ClientPb.getUser                          avgt       3   3.227 ± 1.021   ms/op
ClientPb.listUser                         avgt       3   3.802 ± 0.424   ms/op
ClientPb.createUser                     sample  300767   3.190 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.859           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.113           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.568           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.456           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.155           ms/op
ClientPb.createUser:createUser·p0.9999  sample          20.087           ms/op
ClientPb.createUser:createUser·p1.00    sample          21.758           ms/op
ClientPb.existUser                      sample  304195   3.154 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.112           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.138           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.379           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.505           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.453           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.962           ms/op
ClientPb.existUser:existUser·p1.00      sample          25.002           ms/op
ClientPb.getUser                        sample  287737   3.333 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.294           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.801           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.301           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.972           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.424           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.933           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.884           ms/op
ClientPb.listUser                       sample  256354   3.743 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.739           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.572           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.084           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.334           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.234           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.664           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.299           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.790           ms/op
