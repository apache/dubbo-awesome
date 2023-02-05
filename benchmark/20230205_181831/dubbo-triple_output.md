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
# Warmup Iteration   1: 1.091 ops/ms
# Warmup Iteration   2: 2.257 ops/ms
# Warmup Iteration   3: 4.775 ops/ms
Iteration   1: 5.882 ops/ms
Iteration   2: 5.722 ops/ms
Iteration   3: 5.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.813 ±(99.9%) 1.498 ops/ms [Average]
  (min, avg, max) = (5.722, 5.813, 5.882), stdev = 0.082
  CI (99.9%): [4.315, 7.310] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.652 ops/ms
# Warmup Iteration   2: 4.756 ops/ms
# Warmup Iteration   3: 5.796 ops/ms
Iteration   1: 6.024 ops/ms
Iteration   2: 6.262 ops/ms
Iteration   3: 6.049 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.112 ±(99.9%) 2.390 ops/ms [Average]
  (min, avg, max) = (6.024, 6.112, 6.262), stdev = 0.131
  CI (99.9%): [3.722, 8.501] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.672 ops/ms
# Warmup Iteration   2: 5.244 ops/ms
# Warmup Iteration   3: 5.975 ops/ms
Iteration   1: 5.685 ops/ms
Iteration   2: 5.777 ops/ms
Iteration   3: 6.030 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.831 ±(99.9%) 3.253 ops/ms [Average]
  (min, avg, max) = (5.685, 5.831, 6.030), stdev = 0.178
  CI (99.9%): [2.577, 9.084] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.489 ops/ms
# Warmup Iteration   2: 4.149 ops/ms
# Warmup Iteration   3: 5.143 ops/ms
Iteration   1: 5.012 ops/ms
Iteration   2: 5.069 ops/ms
Iteration   3: 5.127 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.069 ±(99.9%) 1.050 ops/ms [Average]
  (min, avg, max) = (5.012, 5.069, 5.127), stdev = 0.058
  CI (99.9%): [4.019, 6.119] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 18.090 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 6.959 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.699 ±(99.9%) 0.012 ms/op
Iteration   1: 5.452 ±(99.9%) 0.012 ms/op
Iteration   2: 5.458 ±(99.9%) 0.009 ms/op
Iteration   3: 5.439 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.450 ±(99.9%) 0.172 ms/op [Average]
  (min, avg, max) = (5.439, 5.450, 5.458), stdev = 0.009
  CI (99.9%): [5.277, 5.622] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 18.381 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 6.140 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.331 ±(99.9%) 0.007 ms/op
Iteration   1: 5.157 ±(99.9%) 0.009 ms/op
Iteration   2: 5.212 ±(99.9%) 0.010 ms/op
Iteration   3: 5.284 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.218 ±(99.9%) 1.167 ms/op [Average]
  (min, avg, max) = (5.157, 5.218, 5.284), stdev = 0.064
  CI (99.9%): [4.051, 6.384] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 16.640 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 6.236 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.468 ±(99.9%) 0.008 ms/op
Iteration   1: 5.610 ±(99.9%) 0.014 ms/op
Iteration   2: 5.563 ±(99.9%) 0.011 ms/op
Iteration   3: 5.319 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.497 ±(99.9%) 2.842 ms/op [Average]
  (min, avg, max) = (5.319, 5.497, 5.610), stdev = 0.156
  CI (99.9%): [2.655, 8.339] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 20.726 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 7.547 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 6.556 ±(99.9%) 0.014 ms/op
Iteration   1: 6.316 ±(99.9%) 0.013 ms/op
Iteration   2: 6.079 ±(99.9%) 0.017 ms/op
Iteration   3: 6.399 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.265 ±(99.9%) 3.033 ms/op [Average]
  (min, avg, max) = (6.079, 6.265, 6.399), stdev = 0.166
  CI (99.9%): [3.232, 9.297] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 18.781 ±(99.9%) 0.317 ms/op
# Warmup Iteration   2: 7.248 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 5.960 ±(99.9%) 0.025 ms/op
Iteration   1: 5.425 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.331 ms/op
                 createUser·p0.50:   4.915 ms/op
                 createUser·p0.90:   7.031 ms/op
                 createUser·p0.95:   8.233 ms/op
                 createUser·p0.99:   12.222 ms/op
                 createUser·p0.999:  23.893 ms/op
                 createUser·p0.9999: 32.542 ms/op
                 createUser·p1.00:   35.914 ms/op

Iteration   2: 5.608 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.384 ms/op
                 createUser·p0.50:   5.333 ms/op
                 createUser·p0.90:   7.086 ms/op
                 createUser·p0.95:   7.922 ms/op
                 createUser·p0.99:   10.797 ms/op
                 createUser·p0.999:  25.034 ms/op
                 createUser·p0.9999: 29.698 ms/op
                 createUser·p1.00:   30.638 ms/op

Iteration   3: 5.732 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.249 ms/op
                 createUser·p0.50:   5.423 ms/op
                 createUser·p0.90:   7.397 ms/op
                 createUser·p0.95:   8.077 ms/op
                 createUser·p0.99:   10.617 ms/op
                 createUser·p0.999:  29.038 ms/op
                 createUser·p0.9999: 32.080 ms/op
                 createUser·p1.00:   32.178 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171769
  mean =      5.586 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 72190 
    [ 5.000,  7.500) = 86008 
    [ 7.500, 10.000) = 10663 
    [10.000, 12.500) = 1820 
    [12.500, 15.000) = 619 
    [15.000, 17.500) = 155 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 55 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.249 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      7.193 ms/op
     p(95.0000) =      8.061 ms/op
     p(99.0000) =     11.146 ms/op
     p(99.9000) =     24.740 ms/op
     p(99.9900) =     32.074 ms/op
     p(99.9990) =     35.020 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.191 ±(99.9%) 0.260 ms/op
# Warmup Iteration   2: 5.965 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.485 ±(99.9%) 0.021 ms/op
Iteration   1: 5.443 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   1.954 ms/op
                 existUser·p0.50:   5.046 ms/op
                 existUser·p0.90:   7.193 ms/op
                 existUser·p0.95:   7.938 ms/op
                 existUser·p0.99:   10.207 ms/op
                 existUser·p0.999:  22.193 ms/op
                 existUser·p0.9999: 28.553 ms/op
                 existUser·p1.00:   29.557 ms/op

Iteration   2: 5.403 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.720 ms/op
                 existUser·p0.50:   5.014 ms/op
                 existUser·p0.90:   6.955 ms/op
                 existUser·p0.95:   7.922 ms/op
                 existUser·p0.99:   10.617 ms/op
                 existUser·p0.999:  14.242 ms/op
                 existUser·p0.9999: 27.823 ms/op
                 existUser·p1.00:   28.606 ms/op

Iteration   3: 5.373 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.335 ms/op
                 existUser·p0.50:   5.046 ms/op
                 existUser·p0.90:   6.758 ms/op
                 existUser·p0.95:   7.684 ms/op
                 existUser·p0.99:   10.600 ms/op
                 existUser·p0.999:  25.544 ms/op
                 existUser·p0.9999: 30.545 ms/op
                 existUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 177355
  mean =      5.406 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21 
    [ 2.500,  5.000) = 86433 
    [ 5.000,  7.500) = 79164 
    [ 7.500, 10.000) = 9501 
    [10.000, 12.500) = 1616 
    [12.500, 15.000) = 411 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.720 ms/op
     p(50.0000) =      5.030 ms/op
     p(90.0000) =      6.980 ms/op
     p(95.0000) =      7.873 ms/op
     p(99.0000) =     10.477 ms/op
     p(99.9000) =     16.974 ms/op
     p(99.9900) =     29.795 ms/op
     p(99.9990) =     30.875 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 18.319 ±(99.9%) 0.308 ms/op
# Warmup Iteration   2: 6.794 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.727 ±(99.9%) 0.021 ms/op
Iteration   1: 5.502 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   1.784 ms/op
                 getUser·p0.50:   5.046 ms/op
                 getUser·p0.90:   7.193 ms/op
                 getUser·p0.95:   8.274 ms/op
                 getUser·p0.99:   12.009 ms/op
                 getUser·p0.999:  23.591 ms/op
                 getUser·p0.9999: 28.776 ms/op
                 getUser·p1.00:   29.065 ms/op

Iteration   2: 5.362 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.885 ms/op
                 getUser·p0.50:   5.046 ms/op
                 getUser·p0.90:   6.644 ms/op
                 getUser·p0.95:   7.463 ms/op
                 getUser·p0.99:   10.486 ms/op
                 getUser·p0.999:  24.797 ms/op
                 getUser·p0.9999: 34.210 ms/op
                 getUser·p1.00:   35.127 ms/op

Iteration   3: 5.583 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.666 ms/op
                 getUser·p0.50:   5.145 ms/op
                 getUser·p0.90:   7.381 ms/op
                 getUser·p0.95:   8.233 ms/op
                 getUser·p0.99:   10.650 ms/op
                 getUser·p0.999:  23.512 ms/op
                 getUser·p0.9999: 31.368 ms/op
                 getUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 175083
  mean =      5.481 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 81395 
    [ 5.000,  7.500) = 80589 
    [ 7.500, 10.000) = 10321 
    [10.000, 12.500) = 1886 
    [12.500, 15.000) = 468 
    [15.000, 17.500) = 191 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 39 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 27 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      5.071 ms/op
     p(90.0000) =      7.062 ms/op
     p(95.0000) =      8.045 ms/op
     p(99.0000) =     11.092 ms/op
     p(99.9000) =     24.434 ms/op
     p(99.9900) =     33.882 ms/op
     p(99.9990) =     34.586 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


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
# Warmup Iteration   1: 21.186 ±(99.9%) 0.362 ms/op
# Warmup Iteration   2: 7.956 ±(99.9%) 0.056 ms/op
# Warmup Iteration   3: 6.531 ±(99.9%) 0.026 ms/op
Iteration   1: 6.524 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   3.166 ms/op
                 listUser·p0.50:   6.136 ms/op
                 listUser·p0.90:   8.323 ms/op
                 listUser·p0.95:   9.355 ms/op
                 listUser·p0.99:   11.944 ms/op
                 listUser·p0.999:  26.771 ms/op
                 listUser·p0.9999: 29.829 ms/op
                 listUser·p1.00:   30.081 ms/op

Iteration   2: 6.500 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.777 ms/op
                 listUser·p0.50:   6.128 ms/op
                 listUser·p0.90:   8.086 ms/op
                 listUser·p0.95:   9.110 ms/op
                 listUser·p0.99:   12.665 ms/op
                 listUser·p0.999:  29.418 ms/op
                 listUser·p0.9999: 33.373 ms/op
                 listUser·p1.00:   34.472 ms/op

Iteration   3: 6.463 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.773 ms/op
                 listUser·p0.50:   6.160 ms/op
                 listUser·p0.90:   7.750 ms/op
                 listUser·p0.95:   8.716 ms/op
                 listUser·p0.99:   11.960 ms/op
                 listUser·p0.999:  27.336 ms/op
                 listUser·p0.9999: 32.987 ms/op
                 listUser·p1.00:   38.011 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 147766
  mean =      6.496 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 6998 
    [ 5.000,  7.500) = 118516 
    [ 7.500, 10.000) = 18096 
    [10.000, 12.500) = 2897 
    [12.500, 15.000) = 670 
    [15.000, 17.500) = 249 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 106 
    [27.500, 30.000) = 74 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 22 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.773 ms/op
     p(50.0000) =      6.144 ms/op
     p(90.0000) =      8.053 ms/op
     p(95.0000) =      9.093 ms/op
     p(99.0000) =     12.124 ms/op
     p(99.9000) =     27.508 ms/op
     p(99.9900) =     32.815 ms/op
     p(99.9990) =     37.948 ms/op
     p(99.9999) =     38.011 ms/op
    p(100.0000) =     38.011 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.813 ± 1.498  ops/ms
ClientPb.existUser                       thrpt       3   6.112 ± 2.390  ops/ms
ClientPb.getUser                         thrpt       3   5.831 ± 3.253  ops/ms
ClientPb.listUser                        thrpt       3   5.069 ± 1.050  ops/ms
ClientPb.createUser                       avgt       3   5.450 ± 0.172   ms/op
ClientPb.existUser                        avgt       3   5.218 ± 1.167   ms/op
ClientPb.getUser                          avgt       3   5.497 ± 2.842   ms/op
ClientPb.listUser                         avgt       3   6.265 ± 3.033   ms/op
ClientPb.createUser                     sample  171769   5.586 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.249           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.218           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.193           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.061           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.146           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.740           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.074           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.914           ms/op
ClientPb.existUser                      sample  177355   5.406 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.720           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.030           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.980           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.873           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.477           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.974           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.795           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.900           ms/op
ClientPb.getUser                        sample  175083   5.481 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.885           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.071           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.062           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.045           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.092           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.434           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.882           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.127           ms/op
ClientPb.listUser                       sample  147766   6.496 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.773           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.144           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.053           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.093           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.124           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.508           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.815           ms/op
ClientPb.listUser:listUser·p1.00        sample          38.011           ms/op
