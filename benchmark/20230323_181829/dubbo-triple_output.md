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
# Warmup Iteration   1: 2.582 ops/ms
# Warmup Iteration   2: 6.225 ops/ms
# Warmup Iteration   3: 9.370 ops/ms
Iteration   1: 10.049 ops/ms
Iteration   2: 9.647 ops/ms
Iteration   3: 9.820 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.839 ±(99.9%) 3.687 ops/ms [Average]
  (min, avg, max) = (9.647, 9.839, 10.049), stdev = 0.202
  CI (99.9%): [6.152, 13.526] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.656 ops/ms
# Warmup Iteration   2: 9.527 ops/ms
# Warmup Iteration   3: 10.130 ops/ms
Iteration   1: 10.264 ops/ms
Iteration   2: 9.956 ops/ms
Iteration   3: 10.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.286 ±(99.9%) 6.212 ops/ms [Average]
  (min, avg, max) = (9.956, 10.286, 10.636), stdev = 0.340
  CI (99.9%): [4.074, 16.497] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.556 ops/ms
# Warmup Iteration   2: 9.474 ops/ms
# Warmup Iteration   3: 9.544 ops/ms
Iteration   1: 10.176 ops/ms
Iteration   2: 9.971 ops/ms
Iteration   3: 10.162 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.103 ±(99.9%) 2.086 ops/ms [Average]
  (min, avg, max) = (9.971, 10.103, 10.176), stdev = 0.114
  CI (99.9%): [8.017, 12.189] (assumes normal distribution)


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
# Warmup Iteration   1: 3.255 ops/ms
# Warmup Iteration   2: 7.792 ops/ms
# Warmup Iteration   3: 8.453 ops/ms
Iteration   1: 8.599 ops/ms
Iteration   2: 8.603 ops/ms
Iteration   3: 8.796 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.666 ±(99.9%) 2.056 ops/ms [Average]
  (min, avg, max) = (8.599, 8.666, 8.796), stdev = 0.113
  CI (99.9%): [6.610, 10.722] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 9.140 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.296 ±(99.9%) 0.008 ms/op
Iteration   1: 3.162 ±(99.9%) 0.009 ms/op
Iteration   2: 3.330 ±(99.9%) 0.005 ms/op
Iteration   3: 3.223 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.238 ±(99.9%) 1.546 ms/op [Average]
  (min, avg, max) = (3.162, 3.238, 3.330), stdev = 0.085
  CI (99.9%): [1.693, 4.784] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 8.104 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.451 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.094 ±(99.9%) 0.007 ms/op
Iteration   1: 3.167 ±(99.9%) 0.003 ms/op
Iteration   2: 3.144 ±(99.9%) 0.009 ms/op
Iteration   3: 2.993 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.101 ±(99.9%) 1.726 ms/op [Average]
  (min, avg, max) = (2.993, 3.101, 3.167), stdev = 0.095
  CI (99.9%): [1.375, 4.827] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 7.250 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.370 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.269 ±(99.9%) 0.006 ms/op
Iteration   1: 3.252 ±(99.9%) 0.006 ms/op
Iteration   2: 3.169 ±(99.9%) 0.003 ms/op
Iteration   3: 3.055 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.159 ±(99.9%) 1.802 ms/op [Average]
  (min, avg, max) = (3.055, 3.159, 3.252), stdev = 0.099
  CI (99.9%): [1.357, 4.960] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.904 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.162 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.812 ±(99.9%) 0.005 ms/op
Iteration   1: 3.717 ±(99.9%) 0.008 ms/op
Iteration   2: 3.674 ±(99.9%) 0.011 ms/op
Iteration   3: 3.659 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.683 ±(99.9%) 0.550 ms/op [Average]
  (min, avg, max) = (3.659, 3.683, 3.717), stdev = 0.030
  CI (99.9%): [3.134, 4.233] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.620 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.791 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.127 ±(99.9%) 0.007 ms/op
Iteration   1: 3.179 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.897 ms/op
                 createUser·p0.50:   3.011 ms/op
                 createUser·p0.90:   3.596 ms/op
                 createUser·p0.95:   3.924 ms/op
                 createUser·p0.99:   5.874 ms/op
                 createUser·p0.999:  19.033 ms/op
                 createUser·p0.9999: 21.789 ms/op
                 createUser·p1.00:   22.315 ms/op

Iteration   2: 3.258 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.032 ms/op
                 createUser·p0.50:   3.162 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.358 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  9.974 ms/op
                 createUser·p0.9999: 24.505 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   3: 3.093 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   1.501 ms/op
                 createUser·p0.50:   2.978 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.756 ms/op
                 createUser·p0.99:   5.226 ms/op
                 createUser·p0.999:  15.870 ms/op
                 createUser·p0.9999: 18.907 ms/op
                 createUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 302246
  mean =      3.175 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15281 
    [ 2.500,  5.000) = 280211 
    [ 5.000,  7.500) = 5806 
    [ 7.500, 10.000) = 553 
    [10.000, 12.500) = 43 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 135 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.600 ms/op
     p(95.0000) =      4.059 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     16.343 ms/op
     p(99.9900) =     22.078 ms/op
     p(99.9990) =     25.324 ms/op
     p(99.9999) =     25.428 ms/op
    p(100.0000) =     25.428 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.902 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.170 ±(99.9%) 0.009 ms/op
Iteration   1: 3.030 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.327 ms/op
                 existUser·p0.50:   3.056 ms/op
                 existUser·p0.90:   3.146 ms/op
                 existUser·p0.95:   3.232 ms/op
                 existUser·p0.99:   5.128 ms/op
                 existUser·p0.999:  8.410 ms/op
                 existUser·p0.9999: 21.262 ms/op
                 existUser·p1.00:   22.020 ms/op

Iteration   2: 3.177 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.470 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   4.153 ms/op
                 existUser·p0.99:   5.791 ms/op
                 existUser·p0.999:  11.944 ms/op
                 existUser·p0.9999: 22.051 ms/op
                 existUser·p1.00:   22.446 ms/op

Iteration   3: 3.052 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.959 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.183 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  9.798 ms/op
                 existUser·p0.9999: 21.725 ms/op
                 existUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 311054
  mean =      3.085 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31449 
    [ 2.500,  5.000) = 273725 
    [ 5.000,  7.500) = 5222 
    [ 7.500, 10.000) = 363 
    [10.000, 12.500) = 6 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 125 
    [20.000, 22.500) = 129 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.327 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.314 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =      9.764 ms/op
     p(99.9900) =     21.587 ms/op
     p(99.9990) =     22.435 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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
# Warmup Iteration   1: 8.299 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 3.533 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.376 ±(99.9%) 0.010 ms/op
Iteration   1: 3.356 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.188 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   4.026 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   5.939 ms/op
                 getUser·p0.999:  17.686 ms/op
                 getUser·p0.9999: 22.413 ms/op
                 getUser·p1.00:   22.905 ms/op

Iteration   2: 3.252 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.561 ms/op
                 getUser·p0.50:   3.185 ms/op
                 getUser·p0.90:   3.744 ms/op
                 getUser·p0.95:   4.170 ms/op
                 getUser·p0.99:   5.456 ms/op
                 getUser·p0.999:  11.323 ms/op
                 getUser·p0.9999: 25.017 ms/op
                 getUser·p1.00:   25.559 ms/op

Iteration   3: 3.148 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.681 ms/op
                 getUser·p0.50:   3.109 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   5.726 ms/op
                 getUser·p0.999:  9.065 ms/op
                 getUser·p0.9999: 22.736 ms/op
                 getUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 295236
  mean =      3.250 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24970 
    [ 2.500,  5.000) = 263536 
    [ 5.000,  7.500) = 5835 
    [ 7.500, 10.000) = 464 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      0.561 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.211 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     14.893 ms/op
     p(99.9900) =     24.067 ms/op
     p(99.9990) =     25.462 ms/op
     p(99.9999) =     25.559 ms/op
    p(100.0000) =     25.559 ms/op


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
# Warmup Iteration   1: 8.459 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.958 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.739 ±(99.9%) 0.011 ms/op
Iteration   1: 3.684 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   1.616 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   3.949 ms/op
                 listUser·p0.95:   4.149 ms/op
                 listUser·p0.99:   6.373 ms/op
                 listUser·p0.999:  13.877 ms/op
                 listUser·p0.9999: 22.260 ms/op
                 listUser·p1.00:   23.560 ms/op

Iteration   2: 3.923 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.097 ms/op
                 listUser·p0.50:   3.740 ms/op
                 listUser·p0.90:   4.394 ms/op
                 listUser·p0.95:   5.014 ms/op
                 listUser·p0.99:   7.846 ms/op
                 listUser·p0.999:  13.730 ms/op
                 listUser·p0.9999: 15.431 ms/op
                 listUser·p1.00:   15.483 ms/op

Iteration   3: 3.764 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.425 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.047 ms/op
                 listUser·p0.95:   4.375 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  14.057 ms/op
                 listUser·p0.9999: 17.092 ms/op
                 listUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 253339
  mean =      3.788 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44 
    [ 2.500,  5.000) = 244860 
    [ 5.000,  7.500) = 6383 
    [ 7.500, 10.000) = 1262 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 373 
    [15.000, 17.500) = 98 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.616 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =     13.812 ms/op
     p(99.9900) =     20.797 ms/op
     p(99.9990) =     23.527 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.839 ± 3.687  ops/ms
ClientPb.existUser                       thrpt       3  10.286 ± 6.212  ops/ms
ClientPb.getUser                         thrpt       3  10.103 ± 2.086  ops/ms
ClientPb.listUser                        thrpt       3   8.666 ± 2.056  ops/ms
ClientPb.createUser                       avgt       3   3.238 ± 1.546   ms/op
ClientPb.existUser                        avgt       3   3.101 ± 1.726   ms/op
ClientPb.getUser                          avgt       3   3.159 ± 1.802   ms/op
ClientPb.listUser                         avgt       3   3.683 ± 0.550   ms/op
ClientPb.createUser                     sample  302246   3.175 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.897           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.060           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.600           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.059           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.546           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.343           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.078           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.428           ms/op
ClientPb.existUser                      sample  311054   3.085 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.327           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.056           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.756           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.407           ms/op
ClientPb.existUser:existUser·p0.999     sample           9.764           ms/op
ClientPb.existUser:existUser·p0.9999    sample          21.587           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.560           ms/op
ClientPb.getUser                        sample  295236   3.250 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.561           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.174           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.211           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.710           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.893           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.067           ms/op
ClientPb.getUser:getUser·p1.00          sample          25.559           ms/op
ClientPb.listUser                       sample  253339   3.788 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.616           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.690           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.182           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.489           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.037           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.812           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.797           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.560           ms/op
