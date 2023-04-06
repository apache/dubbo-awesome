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
# Warmup Iteration   1: 0.962 ops/ms
# Warmup Iteration   2: 2.079 ops/ms
# Warmup Iteration   3: 4.829 ops/ms
Iteration   1: 5.325 ops/ms
Iteration   2: 5.894 ops/ms
Iteration   3: 5.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.688 ±(99.9%) 5.748 ops/ms [Average]
  (min, avg, max) = (5.325, 5.688, 5.894), stdev = 0.315
  CI (99.9%): [≈ 0, 11.436] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.651 ops/ms
# Warmup Iteration   2: 4.964 ops/ms
# Warmup Iteration   3: 6.246 ops/ms
Iteration   1: 6.247 ops/ms
Iteration   2: 5.800 ops/ms
Iteration   3: 5.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.997 ±(99.9%) 4.162 ops/ms [Average]
  (min, avg, max) = (5.800, 5.997, 6.247), stdev = 0.228
  CI (99.9%): [1.835, 10.160] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.546 ops/ms
# Warmup Iteration   2: 4.876 ops/ms
# Warmup Iteration   3: 6.021 ops/ms
Iteration   1: 5.985 ops/ms
Iteration   2: 6.188 ops/ms
Iteration   3: 6.052 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.075 ±(99.9%) 1.890 ops/ms [Average]
  (min, avg, max) = (5.985, 6.075, 6.188), stdev = 0.104
  CI (99.9%): [4.185, 7.965] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:10:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.640 ops/ms
# Warmup Iteration   2: 4.512 ops/ms
# Warmup Iteration   3: 5.185 ops/ms
Iteration   1: 5.121 ops/ms
Iteration   2: 5.018 ops/ms
Iteration   3: 5.118 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.086 ±(99.9%) 1.072 ops/ms [Average]
  (min, avg, max) = (5.018, 5.086, 5.121), stdev = 0.059
  CI (99.9%): [4.014, 6.158] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:54
# Fork: 1 of 1
# Warmup Iteration   1: 21.394 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 7.002 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.673 ±(99.9%) 0.008 ms/op
Iteration   1: 5.643 ±(99.9%) 0.009 ms/op
Iteration   2: 5.351 ±(99.9%) 0.012 ms/op
Iteration   3: 5.398 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.464 ±(99.9%) 2.861 ms/op [Average]
  (min, avg, max) = (5.351, 5.464, 5.643), stdev = 0.157
  CI (99.9%): [2.603, 8.325] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:47
# Fork: 1 of 1
# Warmup Iteration   1: 17.320 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.740 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.361 ±(99.9%) 0.010 ms/op
Iteration   1: 5.032 ±(99.9%) 0.011 ms/op
Iteration   2: 5.233 ±(99.9%) 0.007 ms/op
Iteration   3: 4.868 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.045 ±(99.9%) 3.332 ms/op [Average]
  (min, avg, max) = (4.868, 5.045, 5.233), stdev = 0.183
  CI (99.9%): [1.713, 8.376] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 19.686 ±(99.9%) 0.104 ms/op
# Warmup Iteration   2: 6.809 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.494 ±(99.9%) 0.014 ms/op
Iteration   1: 5.536 ±(99.9%) 0.010 ms/op
Iteration   2: 5.424 ±(99.9%) 0.009 ms/op
Iteration   3: 5.322 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.428 ±(99.9%) 1.955 ms/op [Average]
  (min, avg, max) = (5.322, 5.428, 5.536), stdev = 0.107
  CI (99.9%): [3.473, 7.382] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 18.302 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 8.077 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 6.749 ±(99.9%) 0.010 ms/op
Iteration   1: 6.217 ±(99.9%) 0.012 ms/op
Iteration   2: 6.320 ±(99.9%) 0.009 ms/op
Iteration   3: 5.966 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.168 ±(99.9%) 3.315 ms/op [Average]
  (min, avg, max) = (5.966, 6.168, 6.320), stdev = 0.182
  CI (99.9%): [2.852, 9.483] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 17.377 ±(99.9%) 0.278 ms/op
# Warmup Iteration   2: 7.273 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.125 ±(99.9%) 0.033 ms/op
Iteration   1: 5.407 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.146 ms/op
                 createUser·p0.50:   5.014 ms/op
                 createUser·p0.90:   6.898 ms/op
                 createUser·p0.95:   8.036 ms/op
                 createUser·p0.99:   10.928 ms/op
                 createUser·p0.999:  25.482 ms/op
                 createUser·p0.9999: 35.538 ms/op
                 createUser·p1.00:   36.569 ms/op

Iteration   2: 5.360 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.175 ms/op
                 createUser·p0.50:   5.063 ms/op
                 createUser·p0.90:   6.627 ms/op
                 createUser·p0.95:   7.537 ms/op
                 createUser·p0.99:   9.601 ms/op
                 createUser·p0.999:  24.758 ms/op
                 createUser·p0.9999: 29.894 ms/op
                 createUser·p1.00:   30.704 ms/op

Iteration   3: 5.568 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.236 ms/op
                 createUser·p0.50:   5.243 ms/op
                 createUser·p0.90:   7.078 ms/op
                 createUser·p0.95:   8.094 ms/op
                 createUser·p0.99:   10.662 ms/op
                 createUser·p0.999:  29.188 ms/op
                 createUser·p0.9999: 35.406 ms/op
                 createUser·p1.00:   36.176 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 176252
  mean =      5.444 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 79591 
    [ 5.000,  7.500) = 85215 
    [ 7.500, 10.000) = 9130 
    [10.000, 12.500) = 1603 
    [12.500, 15.000) = 390 
    [15.000, 17.500) = 84 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 36 
    [27.500, 30.000) = 62 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 47 
    [35.000, 37.500) = 16 

  Percentiles, ms/op:
      p(0.0000) =      2.146 ms/op
     p(50.0000) =      5.104 ms/op
     p(90.0000) =      6.873 ms/op
     p(95.0000) =      7.873 ms/op
     p(99.0000) =     10.461 ms/op
     p(99.9000) =     25.542 ms/op
     p(99.9900) =     34.931 ms/op
     p(99.9990) =     36.469 ms/op
     p(99.9999) =     36.569 ms/op
    p(100.0000) =     36.569 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.723 ±(99.9%) 0.276 ms/op
# Warmup Iteration   2: 6.282 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.275 ±(99.9%) 0.019 ms/op
Iteration   1: 5.262 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.073 ms/op
                 existUser·p0.50:   4.899 ms/op
                 existUser·p0.90:   6.758 ms/op
                 existUser·p0.95:   7.946 ms/op
                 existUser·p0.99:   10.535 ms/op
                 existUser·p0.999:  19.681 ms/op
                 existUser·p0.9999: 24.369 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   2: 5.224 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.261 ms/op
                 existUser·p0.50:   4.907 ms/op
                 existUser·p0.90:   6.545 ms/op
                 existUser·p0.95:   7.512 ms/op
                 existUser·p0.99:   11.305 ms/op
                 existUser·p0.999:  22.439 ms/op
                 existUser·p0.9999: 31.027 ms/op
                 existUser·p1.00:   31.850 ms/op

Iteration   3: 5.221 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.367 ms/op
                 existUser·p0.50:   4.891 ms/op
                 existUser·p0.90:   6.636 ms/op
                 existUser·p0.95:   7.619 ms/op
                 existUser·p0.99:   9.847 ms/op
                 existUser·p0.999:  14.004 ms/op
                 existUser·p0.9999: 28.769 ms/op
                 existUser·p1.00:   29.426 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 183279
  mean =      5.235 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 100185 
    [ 5.000,  7.500) = 72618 
    [ 7.500, 10.000) = 8170 
    [10.000, 12.500) = 1472 
    [12.500, 15.000) = 468 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.073 ms/op
     p(50.0000) =      4.899 ms/op
     p(90.0000) =      6.636 ms/op
     p(95.0000) =      7.668 ms/op
     p(99.0000) =     10.420 ms/op
     p(99.9000) =     17.367 ms/op
     p(99.9900) =     28.094 ms/op
     p(99.9990) =     31.769 ms/op
     p(99.9999) =     31.850 ms/op
    p(100.0000) =     31.850 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 19.335 ±(99.9%) 0.329 ms/op
# Warmup Iteration   2: 6.865 ±(99.9%) 0.047 ms/op
# Warmup Iteration   3: 5.606 ±(99.9%) 0.025 ms/op
Iteration   1: 5.393 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.552 ms/op
                 getUser·p0.50:   5.087 ms/op
                 getUser·p0.90:   6.644 ms/op
                 getUser·p0.95:   7.651 ms/op
                 getUser·p0.99:   10.535 ms/op
                 getUser·p0.999:  22.435 ms/op
                 getUser·p0.9999: 25.596 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   2: 5.568 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.175 ms/op
                 getUser·p0.50:   5.210 ms/op
                 getUser·p0.90:   6.873 ms/op
                 getUser·p0.95:   8.184 ms/op
                 getUser·p0.99:   11.551 ms/op
                 getUser·p0.999:  19.300 ms/op
                 getUser·p0.9999: 29.853 ms/op
                 getUser·p1.00:   32.211 ms/op

Iteration   3: 5.433 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.748 ms/op
                 getUser·p0.50:   5.161 ms/op
                 getUser·p0.90:   6.701 ms/op
                 getUser·p0.95:   7.635 ms/op
                 getUser·p0.99:   10.027 ms/op
                 getUser·p0.999:  25.210 ms/op
                 getUser·p0.9999: 29.401 ms/op
                 getUser·p1.00:   31.031 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 175564
  mean =      5.464 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 72534 
    [ 5.000,  7.500) = 92554 
    [ 7.500, 10.000) = 8038 
    [10.000, 12.500) = 1672 
    [12.500, 15.000) = 432 
    [15.000, 17.500) = 88 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 73 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.175 ms/op
     p(50.0000) =      5.153 ms/op
     p(90.0000) =      6.742 ms/op
     p(95.0000) =      7.815 ms/op
     p(99.0000) =     10.764 ms/op
     p(99.9000) =     22.522 ms/op
     p(99.9900) =     29.276 ms/op
     p(99.9990) =     31.840 ms/op
     p(99.9999) =     32.211 ms/op
    p(100.0000) =     32.211 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.924 ±(99.9%) 0.332 ms/op
# Warmup Iteration   2: 7.313 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 6.444 ±(99.9%) 0.026 ms/op
Iteration   1: 6.153 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   0.536 ms/op
                 listUser·p0.50:   5.800 ms/op
                 listUser·p0.90:   7.512 ms/op
                 listUser·p0.95:   8.602 ms/op
                 listUser·p0.99:   12.157 ms/op
                 listUser·p0.999:  24.183 ms/op
                 listUser·p0.9999: 27.027 ms/op
                 listUser·p1.00:   28.312 ms/op

Iteration   2: 6.214 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.798 ms/op
                 listUser·p0.50:   5.898 ms/op
                 listUser·p0.90:   7.455 ms/op
                 listUser·p0.95:   8.536 ms/op
                 listUser·p0.99:   11.764 ms/op
                 listUser·p0.999:  28.874 ms/op
                 listUser·p0.9999: 32.848 ms/op
                 listUser·p1.00:   33.358 ms/op

Iteration   3: 6.070 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.729 ms/op
                 listUser·p0.50:   5.652 ms/op
                 listUser·p0.90:   7.619 ms/op
                 listUser·p0.95:   9.191 ms/op
                 listUser·p0.99:   12.304 ms/op
                 listUser·p0.999:  23.208 ms/op
                 listUser·p0.9999: 32.702 ms/op
                 listUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 156079
  mean =      6.145 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 18009 
    [ 5.000,  7.500) = 122234 
    [ 7.500, 10.000) = 11584 
    [10.000, 12.500) = 2898 
    [12.500, 15.000) = 724 
    [15.000, 17.500) = 212 
    [17.500, 20.000) = 97 
    [20.000, 22.500) = 65 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 66 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 38 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.536 ms/op
     p(50.0000) =      5.784 ms/op
     p(90.0000) =      7.520 ms/op
     p(95.0000) =      8.815 ms/op
     p(99.0000) =     12.157 ms/op
     p(99.9000) =     25.327 ms/op
     p(99.9900) =     32.335 ms/op
     p(99.9990) =     33.444 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


# Run complete. Total time: 00:13:19

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.688 ± 5.748  ops/ms
ClientPb.existUser                       thrpt       3   5.997 ± 4.162  ops/ms
ClientPb.getUser                         thrpt       3   6.075 ± 1.890  ops/ms
ClientPb.listUser                        thrpt       3   5.086 ± 1.072  ops/ms
ClientPb.createUser                       avgt       3   5.464 ± 2.861   ms/op
ClientPb.existUser                        avgt       3   5.045 ± 3.332   ms/op
ClientPb.getUser                          avgt       3   5.428 ± 1.955   ms/op
ClientPb.listUser                         avgt       3   6.168 ± 3.315   ms/op
ClientPb.createUser                     sample  176252   5.444 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.146           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.104           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.873           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.873           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.461           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.542           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.931           ms/op
ClientPb.createUser:createUser·p1.00    sample          36.569           ms/op
ClientPb.existUser                      sample  183279   5.235 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.073           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.899           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.636           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.668           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.420           ms/op
ClientPb.existUser:existUser·p0.999     sample          17.367           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.094           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.850           ms/op
ClientPb.getUser                        sample  175564   5.464 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.175           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.153           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.742           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.815           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.764           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.522           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.276           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.211           ms/op
ClientPb.listUser                       sample  156079   6.145 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.536           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.784           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.520           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.815           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.157           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.327           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.335           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.554           ms/op
