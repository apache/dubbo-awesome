# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 0.955 ops/ms
# Warmup Iteration   2: 1.847 ops/ms
# Warmup Iteration   3: 4.271 ops/ms
Iteration   1: 5.190 ops/ms
Iteration   2: 5.435 ops/ms
Iteration   3: 5.491 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.372 ±(99.9%) 2.918 ops/ms [Average]
  (min, avg, max) = (5.190, 5.372, 5.491), stdev = 0.160
  CI (99.9%): [2.454, 8.290] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:17
# Fork: 1 of 1
# Warmup Iteration   1: 1.460 ops/ms
# Warmup Iteration   2: 4.878 ops/ms
# Warmup Iteration   3: 5.956 ops/ms
Iteration   1: 6.145 ops/ms
Iteration   2: 6.201 ops/ms
Iteration   3: 5.923 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.089 ±(99.9%) 2.682 ops/ms [Average]
  (min, avg, max) = (5.923, 6.089, 6.201), stdev = 0.147
  CI (99.9%): [3.408, 8.771] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.296 ops/ms
# Warmup Iteration   2: 3.589 ops/ms
# Warmup Iteration   3: 5.115 ops/ms
Iteration   1: 5.139 ops/ms
Iteration   2: 5.026 ops/ms
Iteration   3: 5.153 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.106 ±(99.9%) 1.273 ops/ms [Average]
  (min, avg, max) = (5.026, 5.106, 5.153), stdev = 0.070
  CI (99.9%): [3.833, 6.378] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.364 ops/ms
# Warmup Iteration   2: 3.536 ops/ms
# Warmup Iteration   3: 4.422 ops/ms
Iteration   1: 4.497 ops/ms
Iteration   2: 4.644 ops/ms
Iteration   3: 4.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.589 ±(99.9%) 1.469 ops/ms [Average]
  (min, avg, max) = (4.497, 4.589, 4.644), stdev = 0.081
  CI (99.9%): [3.120, 6.058] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:54
# Fork: 1 of 1
# Warmup Iteration   1: 21.034 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 7.935 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.299 ±(99.9%) 0.011 ms/op
Iteration   1: 6.209 ±(99.9%) 0.015 ms/op
Iteration   2: 6.330 ±(99.9%) 0.011 ms/op
Iteration   3: 5.954 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.164 ±(99.9%) 3.503 ms/op [Average]
  (min, avg, max) = (5.954, 6.164, 6.330), stdev = 0.192
  CI (99.9%): [2.661, 9.667] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:47
# Fork: 1 of 1
# Warmup Iteration   1: 20.079 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 6.539 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.709 ±(99.9%) 0.010 ms/op
Iteration   1: 5.416 ±(99.9%) 0.010 ms/op
Iteration   2: 5.228 ±(99.9%) 0.007 ms/op
Iteration   3: 5.306 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.317 ±(99.9%) 1.721 ms/op [Average]
  (min, avg, max) = (5.228, 5.317, 5.416), stdev = 0.094
  CI (99.9%): [3.596, 7.037] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 20.925 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 7.641 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.205 ±(99.9%) 0.009 ms/op
Iteration   1: 6.304 ±(99.9%) 0.010 ms/op
Iteration   2: 6.251 ±(99.9%) 0.011 ms/op
Iteration   3: 6.372 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.309 ±(99.9%) 1.111 ms/op [Average]
  (min, avg, max) = (6.251, 6.309, 6.372), stdev = 0.061
  CI (99.9%): [5.198, 7.420] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 26.592 ±(99.9%) 0.158 ms/op
# Warmup Iteration   2: 11.304 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 7.828 ±(99.9%) 0.017 ms/op
Iteration   1: 7.683 ±(99.9%) 0.024 ms/op
Iteration   2: 7.621 ±(99.9%) 0.013 ms/op
Iteration   3: 7.688 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.664 ±(99.9%) 0.681 ms/op [Average]
  (min, avg, max) = (7.621, 7.664, 7.688), stdev = 0.037
  CI (99.9%): [6.983, 8.346] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 24.159 ±(99.9%) 0.429 ms/op
# Warmup Iteration   2: 8.302 ±(99.9%) 0.067 ms/op
# Warmup Iteration   3: 7.079 ±(99.9%) 0.043 ms/op
Iteration   1: 6.782 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   2.654 ms/op
                 createUser·p0.50:   6.070 ms/op
                 createUser·p0.90:   9.601 ms/op
                 createUser·p0.95:   11.207 ms/op
                 createUser·p0.99:   16.679 ms/op
                 createUser·p0.999:  28.764 ms/op
                 createUser·p0.9999: 31.056 ms/op
                 createUser·p1.00:   35.521 ms/op

Iteration   2: 6.426 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   2.494 ms/op
                 createUser·p0.50:   5.784 ms/op
                 createUser·p0.90:   8.864 ms/op
                 createUser·p0.95:   10.355 ms/op
                 createUser·p0.99:   14.909 ms/op
                 createUser·p0.999:  31.594 ms/op
                 createUser·p0.9999: 39.584 ms/op
                 createUser·p1.00:   39.715 ms/op

Iteration   3: 6.755 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   2.560 ms/op
                 createUser·p0.50:   6.111 ms/op
                 createUser·p0.90:   9.503 ms/op
                 createUser·p0.95:   10.964 ms/op
                 createUser·p0.99:   15.532 ms/op
                 createUser·p0.999:  26.464 ms/op
                 createUser·p0.9999: 42.402 ms/op
                 createUser·p1.00:   46.858 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 144377
  mean =      6.650 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 19222 
    [ 5.000, 10.000) = 114587 
    [10.000, 15.000) = 8816 
    [15.000, 20.000) = 1321 
    [20.000, 25.000) = 199 
    [25.000, 30.000) = 122 
    [30.000, 35.000) = 45 
    [35.000, 40.000) = 53 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      2.494 ms/op
     p(50.0000) =      5.988 ms/op
     p(90.0000) =      9.322 ms/op
     p(95.0000) =     10.879 ms/op
     p(99.0000) =     15.630 ms/op
     p(99.9000) =     28.688 ms/op
     p(99.9900) =     39.920 ms/op
     p(99.9990) =     45.113 ms/op
     p(99.9999) =     46.858 ms/op
    p(100.0000) =     46.858 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 25.587 ±(99.9%) 0.517 ms/op
# Warmup Iteration   2: 9.311 ±(99.9%) 0.088 ms/op
# Warmup Iteration   3: 6.434 ±(99.9%) 0.033 ms/op
Iteration   1: 6.089 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   2.421 ms/op
                 existUser·p0.50:   5.554 ms/op
                 existUser·p0.90:   8.487 ms/op
                 existUser·p0.95:   10.011 ms/op
                 existUser·p0.99:   12.960 ms/op
                 existUser·p0.999:  22.118 ms/op
                 existUser·p0.9999: 29.661 ms/op
                 existUser·p1.00:   30.441 ms/op

Iteration   2: 5.609 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.367 ms/op
                 existUser·p0.50:   5.235 ms/op
                 existUser·p0.90:   6.988 ms/op
                 existUser·p0.95:   8.307 ms/op
                 existUser·p0.99:   11.649 ms/op
                 existUser·p0.999:  28.574 ms/op
                 existUser·p0.9999: 34.669 ms/op
                 existUser·p1.00:   35.324 ms/op

Iteration   3: 5.419 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.564 ms/op
                 existUser·p0.50:   5.112 ms/op
                 existUser·p0.90:   6.595 ms/op
                 existUser·p0.95:   7.649 ms/op
                 existUser·p0.99:   10.699 ms/op
                 existUser·p0.999:  31.194 ms/op
                 existUser·p0.9999: 34.275 ms/op
                 existUser·p1.00:   36.569 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 168564
  mean =      5.692 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 56733 
    [ 5.000,  7.500) = 97021 
    [ 7.500, 10.000) = 10011 
    [10.000, 12.500) = 3440 
    [12.500, 15.000) = 927 
    [15.000, 17.500) = 152 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 4 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 62 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      2.367 ms/op
     p(50.0000) =      5.284 ms/op
     p(90.0000) =      7.242 ms/op
     p(95.0000) =      8.831 ms/op
     p(99.0000) =     12.124 ms/op
     p(99.9000) =     24.019 ms/op
     p(99.9900) =     34.537 ms/op
     p(99.9990) =     36.210 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.985 ±(99.9%) 0.382 ms/op
# Warmup Iteration   2: 8.395 ±(99.9%) 0.072 ms/op
# Warmup Iteration   3: 6.143 ±(99.9%) 0.027 ms/op
Iteration   1: 6.048 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   2.118 ms/op
                 getUser·p0.50:   5.661 ms/op
                 getUser·p0.90:   7.602 ms/op
                 getUser·p0.95:   9.011 ms/op
                 getUser·p0.99:   12.141 ms/op
                 getUser·p0.999:  30.260 ms/op
                 getUser·p0.9999: 54.803 ms/op
                 getUser·p1.00:   71.303 ms/op

Iteration   2: 5.983 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   2.617 ms/op
                 getUser·p0.50:   5.497 ms/op
                 getUser·p0.90:   7.651 ms/op
                 getUser·p0.95:   9.159 ms/op
                 getUser·p0.99:   13.763 ms/op
                 getUser·p0.999:  31.722 ms/op
                 getUser·p0.9999: 53.363 ms/op
                 getUser·p1.00:   56.558 ms/op

Iteration   3: 6.422 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   2.662 ms/op
                 getUser·p0.50:   5.833 ms/op
                 getUser·p0.90:   8.962 ms/op
                 getUser·p0.95:   10.404 ms/op
                 getUser·p0.99:   13.681 ms/op
                 getUser·p0.999:  30.355 ms/op
                 getUser·p0.9999: 47.253 ms/op
                 getUser·p1.00:   47.579 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 155808
  mean =      6.145 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 31200 
    [ 5.000, 10.000) = 117982 
    [10.000, 15.000) = 5840 
    [15.000, 20.000) = 489 
    [20.000, 25.000) = 89 
    [25.000, 30.000) = 34 
    [30.000, 35.000) = 82 
    [35.000, 40.000) = 6 
    [40.000, 45.000) = 29 
    [45.000, 50.000) = 23 
    [50.000, 55.000) = 25 
    [55.000, 60.000) = 8 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 0 
    [70.000, 75.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.118 ms/op
     p(50.0000) =      5.652 ms/op
     p(90.0000) =      8.028 ms/op
     p(95.0000) =      9.650 ms/op
     p(99.0000) =     13.156 ms/op
     p(99.9000) =     30.906 ms/op
     p(99.9900) =     54.133 ms/op
     p(99.9990) =     63.074 ms/op
     p(99.9999) =     71.303 ms/op
    p(100.0000) =     71.303 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 24.995 ±(99.9%) 0.443 ms/op
# Warmup Iteration   2: 8.456 ±(99.9%) 0.070 ms/op
# Warmup Iteration   3: 7.240 ±(99.9%) 0.038 ms/op
Iteration   1: 6.851 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   2.712 ms/op
                 listUser·p0.50:   6.390 ms/op
                 listUser·p0.90:   8.651 ms/op
                 listUser·p0.95:   10.289 ms/op
                 listUser·p0.99:   13.566 ms/op
                 listUser·p0.999:  32.116 ms/op
                 listUser·p0.9999: 36.350 ms/op
                 listUser·p1.00:   38.273 ms/op

Iteration   2: 7.129 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   2.499 ms/op
                 listUser·p0.50:   6.529 ms/op
                 listUser·p0.90:   9.535 ms/op
                 listUser·p0.95:   11.158 ms/op
                 listUser·p0.99:   14.500 ms/op
                 listUser·p0.999:  33.494 ms/op
                 listUser·p0.9999: 39.258 ms/op
                 listUser·p1.00:   39.846 ms/op

Iteration   3: 7.446 ±(99.9%) 0.037 ms/op
                 listUser·p0.00:   3.731 ms/op
                 listUser·p0.50:   6.808 ms/op
                 listUser·p0.90:   9.961 ms/op
                 listUser·p0.95:   11.649 ms/op
                 listUser·p0.99:   15.696 ms/op
                 listUser·p0.999:  34.537 ms/op
                 listUser·p0.9999: 40.528 ms/op
                 listUser·p1.00:   41.091 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 134505
  mean =      7.133 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2674 
    [ 5.000, 10.000) = 121319 
    [10.000, 15.000) = 9279 
    [15.000, 20.000) = 910 
    [20.000, 25.000) = 65 
    [25.000, 30.000) = 57 
    [30.000, 35.000) = 132 
    [35.000, 40.000) = 63 
    [40.000, 45.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      2.499 ms/op
     p(50.0000) =      6.570 ms/op
     p(90.0000) =      9.404 ms/op
     p(95.0000) =     11.026 ms/op
     p(99.0000) =     14.762 ms/op
     p(99.9000) =     33.079 ms/op
     p(99.9900) =     39.358 ms/op
     p(99.9990) =     41.068 ms/op
     p(99.9999) =     41.091 ms/op
    p(100.0000) =     41.091 ms/op


# Run complete. Total time: 00:13:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.372 ± 2.918  ops/ms
ClientPb.existUser                       thrpt       3   6.089 ± 2.682  ops/ms
ClientPb.getUser                         thrpt       3   5.106 ± 1.273  ops/ms
ClientPb.listUser                        thrpt       3   4.589 ± 1.469  ops/ms
ClientPb.createUser                       avgt       3   6.164 ± 3.503   ms/op
ClientPb.existUser                        avgt       3   5.317 ± 1.721   ms/op
ClientPb.getUser                          avgt       3   6.309 ± 1.111   ms/op
ClientPb.listUser                         avgt       3   7.664 ± 0.681   ms/op
ClientPb.createUser                     sample  144377   6.650 ± 0.021   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.494           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.988           ms/op
ClientPb.createUser:createUser·p0.90    sample           9.322           ms/op
ClientPb.createUser:createUser·p0.95    sample          10.879           ms/op
ClientPb.createUser:createUser·p0.99    sample          15.630           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.688           ms/op
ClientPb.createUser:createUser·p0.9999  sample          39.920           ms/op
ClientPb.createUser:createUser·p1.00    sample          46.858           ms/op
ClientPb.existUser                      sample  168564   5.692 ± 0.014   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.367           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.284           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.242           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.831           ms/op
ClientPb.existUser:existUser·p0.99      sample          12.124           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.019           ms/op
ClientPb.existUser:existUser·p0.9999    sample          34.537           ms/op
ClientPb.existUser:existUser·p1.00      sample          36.569           ms/op
ClientPb.getUser                        sample  155808   6.145 ± 0.018   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.118           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.652           ms/op
ClientPb.getUser:getUser·p0.90          sample           8.028           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.650           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.156           ms/op
ClientPb.getUser:getUser·p0.999         sample          30.906           ms/op
ClientPb.getUser:getUser·p0.9999        sample          54.133           ms/op
ClientPb.getUser:getUser·p1.00          sample          71.303           ms/op
ClientPb.listUser                       sample  134505   7.133 ± 0.020   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.499           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.570           ms/op
ClientPb.listUser:listUser·p0.90        sample           9.404           ms/op
ClientPb.listUser:listUser·p0.95        sample          11.026           ms/op
ClientPb.listUser:listUser·p0.99        sample          14.762           ms/op
ClientPb.listUser:listUser·p0.999       sample          33.079           ms/op
ClientPb.listUser:listUser·p0.9999      sample          39.358           ms/op
ClientPb.listUser:listUser·p1.00        sample          41.091           ms/op
