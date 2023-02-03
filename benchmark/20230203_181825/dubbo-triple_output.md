# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.563 ops/ms
# Warmup Iteration   2: 6.018 ops/ms
# Warmup Iteration   3: 9.260 ops/ms
Iteration   1: 9.913 ops/ms
Iteration   2: 9.990 ops/ms
Iteration   3: 10.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.985 ±(99.9%) 1.280 ops/ms [Average]
  (min, avg, max) = (9.913, 9.985, 10.053), stdev = 0.070
  CI (99.9%): [8.705, 11.265] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.585 ops/ms
# Warmup Iteration   2: 9.675 ops/ms
# Warmup Iteration   3: 10.301 ops/ms
Iteration   1: 10.704 ops/ms
Iteration   2: 10.621 ops/ms
Iteration   3: 10.185 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.503 ±(99.9%) 5.086 ops/ms [Average]
  (min, avg, max) = (10.185, 10.503, 10.704), stdev = 0.279
  CI (99.9%): [5.417, 15.589] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.165 ops/ms
# Warmup Iteration   2: 9.468 ops/ms
# Warmup Iteration   3: 9.392 ops/ms
Iteration   1: 10.031 ops/ms
Iteration   2: 9.894 ops/ms
Iteration   3: 10.219 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.048 ±(99.9%) 2.977 ops/ms [Average]
  (min, avg, max) = (9.894, 10.048, 10.219), stdev = 0.163
  CI (99.9%): [7.072, 13.025] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.657 ops/ms
# Warmup Iteration   2: 7.810 ops/ms
# Warmup Iteration   3: 8.421 ops/ms
Iteration   1: 8.519 ops/ms
Iteration   2: 8.568 ops/ms
Iteration   3: 8.480 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.522 ±(99.9%) 0.806 ops/ms [Average]
  (min, avg, max) = (8.480, 8.522, 8.568), stdev = 0.044
  CI (99.9%): [7.716, 9.328] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 9.052 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.575 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.266 ±(99.9%) 0.003 ms/op
Iteration   1: 3.179 ±(99.9%) 0.003 ms/op
Iteration   2: 3.149 ±(99.9%) 0.005 ms/op
Iteration   3: 3.228 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.185 ±(99.9%) 0.729 ms/op [Average]
  (min, avg, max) = (3.149, 3.185, 3.228), stdev = 0.040
  CI (99.9%): [2.457, 3.914] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.131 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.003 ms/op
Iteration   1: 3.005 ±(99.9%) 0.006 ms/op
Iteration   2: 3.155 ±(99.9%) 0.005 ms/op
Iteration   3: 3.147 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.102 ±(99.9%) 1.531 ms/op [Average]
  (min, avg, max) = (3.005, 3.102, 3.155), stdev = 0.084
  CI (99.9%): [1.571, 4.633] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 7.162 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.544 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.268 ±(99.9%) 0.003 ms/op
Iteration   1: 3.277 ±(99.9%) 0.004 ms/op
Iteration   2: 3.251 ±(99.9%) 0.004 ms/op
Iteration   3: 3.325 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.285 ±(99.9%) 0.680 ms/op [Average]
  (min, avg, max) = (3.251, 3.285, 3.325), stdev = 0.037
  CI (99.9%): [2.604, 3.965] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 8.515 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.399 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.772 ±(99.9%) 0.006 ms/op
Iteration   1: 3.694 ±(99.9%) 0.009 ms/op
Iteration   2: 3.752 ±(99.9%) 0.006 ms/op
Iteration   3: 3.719 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.722 ±(99.9%) 0.529 ms/op [Average]
  (min, avg, max) = (3.694, 3.722, 3.752), stdev = 0.029
  CI (99.9%): [3.193, 4.251] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 8.232 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.548 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.158 ±(99.9%) 0.008 ms/op
Iteration   1: 3.112 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.346 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.486 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   5.325 ms/op
                 createUser·p0.999:  18.442 ms/op
                 createUser·p0.9999: 21.192 ms/op
                 createUser·p1.00:   22.807 ms/op

Iteration   2: 3.152 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.015 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   5.472 ms/op
                 createUser·p0.999:  16.018 ms/op
                 createUser·p0.9999: 22.442 ms/op
                 createUser·p1.00:   23.167 ms/op

Iteration   3: 3.108 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.079 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.498 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   5.292 ms/op
                 createUser·p0.999:  8.621 ms/op
                 createUser·p0.9999: 17.012 ms/op
                 createUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 306777
  mean =      3.124 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9324 
    [ 2.500,  5.000) = 292999 
    [ 5.000,  7.500) = 3626 
    [ 7.500, 10.000) = 414 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 89 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.071 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =     14.270 ms/op
     p(99.9900) =     21.375 ms/op
     p(99.9990) =     22.900 ms/op
     p(99.9999) =     23.167 ms/op
    p(100.0000) =     23.167 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 7.597 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.126 ±(99.9%) 0.008 ms/op
Iteration   1: 3.031 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   1.311 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.449 ms/op
                 existUser·p0.99:   5.186 ms/op
                 existUser·p0.999:  8.471 ms/op
                 existUser·p0.9999: 19.869 ms/op
                 existUser·p1.00:   20.414 ms/op

Iteration   2: 3.229 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.831 ms/op
                 existUser·p0.50:   3.166 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   4.051 ms/op
                 existUser·p0.99:   5.063 ms/op
                 existUser·p0.999:  10.568 ms/op
                 existUser·p0.9999: 25.628 ms/op
                 existUser·p1.00:   26.477 ms/op

Iteration   3: 3.258 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.825 ms/op
                 existUser·p0.50:   3.129 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.145 ms/op
                 existUser·p0.999:  11.878 ms/op
                 existUser·p0.9999: 20.709 ms/op
                 existUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 302735
  mean =      3.169 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20669 
    [ 2.500,  5.000) = 276888 
    [ 5.000,  7.500) = 4532 
    [ 7.500, 10.000) = 248 
    [10.000, 12.500) = 110 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 140 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.825 ms/op
     p(50.0000) =      3.092 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.981 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =     10.928 ms/op
     p(99.9900) =     24.829 ms/op
     p(99.9990) =     26.307 ms/op
     p(99.9999) =     26.477 ms/op
    p(100.0000) =     26.477 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.318 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 3.468 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.009 ms/op
Iteration   1: 3.155 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.595 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.416 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   6.062 ms/op
                 getUser·p0.999:  13.264 ms/op
                 getUser·p0.9999: 18.411 ms/op
                 getUser·p1.00:   19.300 ms/op

Iteration   2: 3.168 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.269 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.453 ms/op
                 getUser·p0.95:   3.719 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  15.287 ms/op
                 getUser·p0.9999: 22.345 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   3: 3.247 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.544 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.621 ms/op
                 getUser·p0.95:   3.985 ms/op
                 getUser·p0.99:   5.628 ms/op
                 getUser·p0.999:  10.650 ms/op
                 getUser·p0.9999: 29.824 ms/op
                 getUser·p1.00:   31.162 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 300839
  mean =      3.189 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15428 
    [ 2.500,  5.000) = 278917 
    [ 5.000,  7.500) = 5667 
    [ 7.500, 10.000) = 407 
    [10.000, 12.500) = 60 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.269 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.883 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     14.516 ms/op
     p(99.9900) =     28.273 ms/op
     p(99.9990) =     30.505 ms/op
     p(99.9999) =     31.162 ms/op
    p(100.0000) =     31.162 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 8.225 ±(99.9%) 0.100 ms/op
# Warmup Iteration   2: 3.950 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.012 ms/op
Iteration   1: 3.782 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.794 ms/op
                 listUser·p0.50:   3.596 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.406 ms/op
                 listUser·p0.999:  15.740 ms/op
                 listUser·p0.9999: 35.359 ms/op
                 listUser·p1.00:   38.666 ms/op

Iteration   2: 3.781 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   3.654 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  13.214 ms/op
                 listUser·p0.9999: 15.264 ms/op
                 listUser·p1.00:   18.907 ms/op

Iteration   3: 3.666 ±(99.9%) 0.007 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.592 ms/op
                 listUser·p0.90:   3.928 ms/op
                 listUser·p0.95:   4.108 ms/op
                 listUser·p0.99:   5.743 ms/op
                 listUser·p0.999:  12.288 ms/op
                 listUser·p0.9999: 14.242 ms/op
                 listUser·p1.00:   14.402 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256344
  mean =      3.742 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 87 
    [ 2.500,  5.000) = 247326 
    [ 5.000,  7.500) = 6980 
    [ 7.500, 10.000) = 1266 
    [10.000, 12.500) = 349 
    [12.500, 15.000) = 227 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.794 ms/op
     p(50.0000) =      3.617 ms/op
     p(90.0000) =      4.026 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     13.238 ms/op
     p(99.9900) =     26.733 ms/op
     p(99.9990) =     38.183 ms/op
     p(99.9999) =     38.666 ms/op
    p(100.0000) =     38.666 ms/op


# Run complete. Total time: 00:13:08

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.985 ± 1.280  ops/ms
ClientPb.existUser                       thrpt       3  10.503 ± 5.086  ops/ms
ClientPb.getUser                         thrpt       3  10.048 ± 2.977  ops/ms
ClientPb.listUser                        thrpt       3   8.522 ± 0.806  ops/ms
ClientPb.createUser                       avgt       3   3.185 ± 0.729   ms/op
ClientPb.existUser                        avgt       3   3.102 ± 1.531   ms/op
ClientPb.getUser                          avgt       3   3.285 ± 0.680   ms/op
ClientPb.listUser                         avgt       3   3.722 ± 0.529   ms/op
ClientPb.createUser                     sample  306777   3.124 ± 0.004   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.071           ms/op
ClientPb.createUser:createUser·p0.50    sample           2.994           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.502           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.789           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.333           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.270           ms/op
ClientPb.createUser:createUser·p0.9999  sample          21.375           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.167           ms/op
ClientPb.existUser                      sample  302735   3.169 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.825           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.092           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.637           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.981           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.423           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.928           ms/op
ClientPb.existUser:existUser·p0.9999    sample          24.829           ms/op
ClientPb.existUser:existUser·p1.00      sample          26.477           ms/op
ClientPb.getUser                        sample  300839   3.189 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.269           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.506           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.883           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.734           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.516           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.273           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.162           ms/op
ClientPb.listUser                       sample  256344   3.742 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.794           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.617           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.026           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.309           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.963           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.238           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.733           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.666           ms/op
