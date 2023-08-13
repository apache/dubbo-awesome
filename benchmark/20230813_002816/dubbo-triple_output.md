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
# Warmup Iteration   1: 1.752 ops/ms
# Warmup Iteration   2: 4.111 ops/ms
# Warmup Iteration   3: 7.562 ops/ms
Iteration   1: 7.397 ops/ms
Iteration   2: 7.968 ops/ms
Iteration   3: 8.090 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.818 ±(99.9%) 6.748 ops/ms [Average]
  (min, avg, max) = (7.397, 7.818, 8.090), stdev = 0.370
  CI (99.9%): [1.071, 14.566] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.076 ops/ms
# Warmup Iteration   2: 6.645 ops/ms
# Warmup Iteration   3: 7.859 ops/ms
Iteration   1: 8.376 ops/ms
Iteration   2: 8.221 ops/ms
Iteration   3: 8.136 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.244 ±(99.9%) 2.214 ops/ms [Average]
  (min, avg, max) = (8.136, 8.244, 8.376), stdev = 0.121
  CI (99.9%): [6.031, 10.458] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.257 ops/ms
# Warmup Iteration   2: 7.200 ops/ms
# Warmup Iteration   3: 7.815 ops/ms
Iteration   1: 8.114 ops/ms
Iteration   2: 8.000 ops/ms
Iteration   3: 8.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.045 ±(99.9%) 1.102 ops/ms [Average]
  (min, avg, max) = (8.000, 8.045, 8.114), stdev = 0.060
  CI (99.9%): [6.943, 9.148] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.040 ops/ms
# Warmup Iteration   2: 6.142 ops/ms
# Warmup Iteration   3: 6.490 ops/ms
Iteration   1: 6.559 ops/ms
Iteration   2: 6.569 ops/ms
Iteration   3: 6.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.593 ±(99.9%) 0.904 ops/ms [Average]
  (min, avg, max) = (6.559, 6.593, 6.650), stdev = 0.050
  CI (99.9%): [5.688, 7.497] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 14.915 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.060 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.390 ±(99.9%) 0.005 ms/op
Iteration   1: 4.101 ±(99.9%) 0.006 ms/op
Iteration   2: 4.044 ±(99.9%) 0.011 ms/op
Iteration   3: 3.986 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.043 ±(99.9%) 1.050 ms/op [Average]
  (min, avg, max) = (3.986, 4.043, 4.101), stdev = 0.058
  CI (99.9%): [2.993, 5.094] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 11.898 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.556 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.076 ±(99.9%) 0.003 ms/op
Iteration   1: 3.860 ±(99.9%) 0.009 ms/op
Iteration   2: 3.766 ±(99.9%) 0.008 ms/op
Iteration   3: 3.862 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.830 ±(99.9%) 1.008 ms/op [Average]
  (min, avg, max) = (3.766, 3.830, 3.862), stdev = 0.055
  CI (99.9%): [2.822, 4.838] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 14.462 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.161 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.403 ±(99.9%) 0.005 ms/op
Iteration   1: 4.017 ±(99.9%) 0.004 ms/op
Iteration   2: 4.186 ±(99.9%) 0.004 ms/op
Iteration   3: 4.099 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.101 ±(99.9%) 1.546 ms/op [Average]
  (min, avg, max) = (4.017, 4.101, 4.186), stdev = 0.085
  CI (99.9%): [2.555, 5.646] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 13.223 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 5.220 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.791 ±(99.9%) 0.007 ms/op
Iteration   1: 4.852 ±(99.9%) 0.005 ms/op
Iteration   2: 4.652 ±(99.9%) 0.012 ms/op
Iteration   3: 4.834 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.779 ±(99.9%) 2.021 ms/op [Average]
  (min, avg, max) = (4.652, 4.779, 4.852), stdev = 0.111
  CI (99.9%): [2.758, 6.800] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.481 ±(99.9%) 0.170 ms/op
# Warmup Iteration   2: 5.164 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.540 ±(99.9%) 0.019 ms/op
Iteration   1: 4.061 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.919 ms/op
                 createUser·p0.50:   3.912 ms/op
                 createUser·p0.90:   4.645 ms/op
                 createUser·p0.95:   5.128 ms/op
                 createUser·p0.99:   7.578 ms/op
                 createUser·p0.999:  23.396 ms/op
                 createUser·p0.9999: 26.214 ms/op
                 createUser·p1.00:   27.722 ms/op

Iteration   2: 4.008 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   2.044 ms/op
                 createUser·p0.50:   3.854 ms/op
                 createUser·p0.90:   4.448 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   7.668 ms/op
                 createUser·p0.999:  13.749 ms/op
                 createUser·p0.9999: 27.525 ms/op
                 createUser·p1.00:   28.180 ms/op

Iteration   3: 4.172 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.606 ms/op
                 createUser·p0.50:   3.957 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   5.849 ms/op
                 createUser·p0.99:   8.684 ms/op
                 createUser·p0.999:  27.986 ms/op
                 createUser·p0.9999: 30.256 ms/op
                 createUser·p1.00:   38.076 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 235222
  mean =      4.079 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 341 
    [ 2.500,  5.000) = 220037 
    [ 5.000,  7.500) = 11943 
    [ 7.500, 10.000) = 1983 
    [10.000, 12.500) = 489 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 82 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.606 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.284 ms/op
     p(99.0000) =      7.954 ms/op
     p(99.9000) =     24.150 ms/op
     p(99.9900) =     29.867 ms/op
     p(99.9990) =     32.090 ms/op
     p(99.9999) =     38.076 ms/op
    p(100.0000) =     38.076 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 11.401 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.330 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.027 ±(99.9%) 0.013 ms/op
Iteration   1: 3.982 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.219 ms/op
                 existUser·p0.50:   3.801 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   5.276 ms/op
                 existUser·p0.99:   8.126 ms/op
                 existUser·p0.999:  22.413 ms/op
                 existUser·p0.9999: 24.902 ms/op
                 existUser·p1.00:   25.985 ms/op

Iteration   2: 3.884 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.821 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   7.036 ms/op
                 existUser·p0.999:  12.993 ms/op
                 existUser·p0.9999: 36.161 ms/op
                 existUser·p1.00:   37.290 ms/op

Iteration   3: 4.009 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.720 ms/op
                 existUser·p0.50:   3.793 ms/op
                 existUser·p0.90:   4.637 ms/op
                 existUser·p0.95:   5.267 ms/op
                 existUser·p0.99:   8.217 ms/op
                 existUser·p0.999:  14.975 ms/op
                 existUser·p0.9999: 32.605 ms/op
                 existUser·p1.00:   33.391 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 242524
  mean =      3.958 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 394 
    [ 2.500,  5.000) = 228705 
    [ 5.000,  7.500) = 10363 
    [ 7.500, 10.000) = 2210 
    [10.000, 12.500) = 445 
    [12.500, 15.000) = 165 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 82 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      1.219 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.456 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      7.946 ms/op
     p(99.9000) =     14.991 ms/op
     p(99.9900) =     35.521 ms/op
     p(99.9990) =     36.607 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 12.197 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 4.667 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.231 ±(99.9%) 0.016 ms/op
Iteration   1: 3.944 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.597 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.833 ms/op
                 getUser·p0.99:   7.840 ms/op
                 getUser·p0.999:  23.435 ms/op
                 getUser·p0.9999: 31.261 ms/op
                 getUser·p1.00:   32.113 ms/op

Iteration   2: 3.915 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.618 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.432 ms/op
                 getUser·p0.95:   4.801 ms/op
                 getUser·p0.99:   7.221 ms/op
                 getUser·p0.999:  13.222 ms/op
                 getUser·p0.9999: 29.617 ms/op
                 getUser·p1.00:   30.802 ms/op

Iteration   3: 3.948 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.421 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   4.719 ms/op
                 getUser·p0.99:   7.281 ms/op
                 getUser·p0.999:  27.849 ms/op
                 getUser·p0.9999: 30.168 ms/op
                 getUser·p1.00:   32.702 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 243829
  mean =      3.936 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 90 
    [ 2.500,  5.000) = 234090 
    [ 5.000,  7.500) = 7204 
    [ 7.500, 10.000) = 1684 
    [10.000, 12.500) = 420 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 46 
    [27.500, 30.000) = 142 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.421 ms/op
     p(50.0000) =      3.785 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     23.244 ms/op
     p(99.9900) =     30.245 ms/op
     p(99.9990) =     32.070 ms/op
     p(99.9999) =     32.702 ms/op
    p(100.0000) =     32.702 ms/op


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
# Warmup Iteration   1: 14.521 ±(99.9%) 0.225 ms/op
# Warmup Iteration   2: 5.545 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.932 ±(99.9%) 0.019 ms/op
Iteration   1: 5.074 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.245 ms/op
                 listUser·p0.50:   4.727 ms/op
                 listUser·p0.90:   6.169 ms/op
                 listUser·p0.95:   7.750 ms/op
                 listUser·p0.99:   10.256 ms/op
                 listUser·p0.999:  26.804 ms/op
                 listUser·p0.9999: 34.059 ms/op
                 listUser·p1.00:   34.931 ms/op

Iteration   2: 4.730 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.501 ms/op
                 listUser·p0.50:   4.440 ms/op
                 listUser·p0.90:   5.194 ms/op
                 listUser·p0.95:   6.062 ms/op
                 listUser·p0.99:   9.388 ms/op
                 listUser·p0.999:  18.322 ms/op
                 listUser·p0.9999: 25.419 ms/op
                 listUser·p1.00:   26.477 ms/op

Iteration   3: 4.822 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.605 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   6.316 ms/op
                 listUser·p0.99:   9.847 ms/op
                 listUser·p0.999:  16.630 ms/op
                 listUser·p0.9999: 19.071 ms/op
                 listUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 196942
  mean =      4.871 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20 
    [ 2.500,  5.000) = 157879 
    [ 5.000,  7.500) = 31148 
    [ 7.500, 10.000) = 6069 
    [10.000, 12.500) = 969 
    [12.500, 15.000) = 334 
    [15.000, 17.500) = 274 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.245 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      5.407 ms/op
     p(95.0000) =      6.955 ms/op
     p(99.0000) =      9.781 ms/op
     p(99.9000) =     19.401 ms/op
     p(99.9900) =     32.348 ms/op
     p(99.9990) =     34.359 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.818 ± 6.748  ops/ms
ClientPb.existUser                       thrpt       3   8.244 ± 2.214  ops/ms
ClientPb.getUser                         thrpt       3   8.045 ± 1.102  ops/ms
ClientPb.listUser                        thrpt       3   6.593 ± 0.904  ops/ms
ClientPb.createUser                       avgt       3   4.043 ± 1.050   ms/op
ClientPb.existUser                        avgt       3   3.830 ± 1.008   ms/op
ClientPb.getUser                          avgt       3   4.101 ± 1.546   ms/op
ClientPb.listUser                         avgt       3   4.779 ± 2.021   ms/op
ClientPb.createUser                     sample  235222   4.079 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.606           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.903           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.653           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.284           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.954           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.150           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.867           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.076           ms/op
ClientPb.existUser                      sample  242524   3.958 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.219           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.777           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.456           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.128           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.946           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.991           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.521           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.290           ms/op
ClientPb.getUser                        sample  243829   3.936 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.421           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.399           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.776           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.504           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.244           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.245           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.702           ms/op
ClientPb.listUser                       sample  196942   4.871 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.245           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.407           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.955           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.781           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.401           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.348           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.931           ms/op
