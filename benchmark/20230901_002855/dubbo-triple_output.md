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
# Warmup Iteration   1: 1.576 ops/ms
# Warmup Iteration   2: 3.776 ops/ms
# Warmup Iteration   3: 7.066 ops/ms
Iteration   1: 7.259 ops/ms
Iteration   2: 7.149 ops/ms
Iteration   3: 7.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.299 ±(99.9%) 3.158 ops/ms [Average]
  (min, avg, max) = (7.149, 7.299, 7.488), stdev = 0.173
  CI (99.9%): [4.141, 10.456] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.209 ops/ms
# Warmup Iteration   2: 6.806 ops/ms
# Warmup Iteration   3: 7.885 ops/ms
Iteration   1: 7.999 ops/ms
Iteration   2: 8.161 ops/ms
Iteration   3: 8.168 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.109 ±(99.9%) 1.748 ops/ms [Average]
  (min, avg, max) = (7.999, 8.109, 8.168), stdev = 0.096
  CI (99.9%): [6.362, 9.857] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.019 ops/ms
# Warmup Iteration   2: 6.176 ops/ms
# Warmup Iteration   3: 7.543 ops/ms
Iteration   1: 7.446 ops/ms
Iteration   2: 7.682 ops/ms
Iteration   3: 7.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.589 ±(99.9%) 2.290 ops/ms [Average]
  (min, avg, max) = (7.446, 7.589, 7.682), stdev = 0.126
  CI (99.9%): [5.298, 9.879] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 1.563 ops/ms
# Warmup Iteration   2: 4.834 ops/ms
# Warmup Iteration   3: 6.268 ops/ms
Iteration   1: 6.460 ops/ms
Iteration   2: 6.339 ops/ms
Iteration   3: 6.704 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.501 ±(99.9%) 3.389 ops/ms [Average]
  (min, avg, max) = (6.339, 6.501, 6.704), stdev = 0.186
  CI (99.9%): [3.112, 9.890] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 13.547 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.914 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.471 ±(99.9%) 0.005 ms/op
Iteration   1: 4.269 ±(99.9%) 0.005 ms/op
Iteration   2: 4.135 ±(99.9%) 0.009 ms/op
Iteration   3: 4.179 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.194 ±(99.9%) 1.244 ms/op [Average]
  (min, avg, max) = (4.135, 4.194, 4.269), stdev = 0.068
  CI (99.9%): [2.951, 5.438] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.661 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 4.316 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.135 ±(99.9%) 0.004 ms/op
Iteration   1: 4.033 ±(99.9%) 0.004 ms/op
Iteration   2: 4.033 ±(99.9%) 0.004 ms/op
Iteration   3: 3.933 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.999 ±(99.9%) 1.051 ms/op [Average]
  (min, avg, max) = (3.933, 3.999, 4.033), stdev = 0.058
  CI (99.9%): [2.948, 5.051] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 14.239 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.873 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.284 ±(99.9%) 0.005 ms/op
Iteration   1: 4.253 ±(99.9%) 0.008 ms/op
Iteration   2: 4.144 ±(99.9%) 0.006 ms/op
Iteration   3: 4.087 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.161 ±(99.9%) 1.545 ms/op [Average]
  (min, avg, max) = (4.087, 4.161, 4.253), stdev = 0.085
  CI (99.9%): [2.617, 5.706] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 15.590 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.727 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.946 ±(99.9%) 0.009 ms/op
Iteration   1: 4.932 ±(99.9%) 0.008 ms/op
Iteration   2: 4.925 ±(99.9%) 0.010 ms/op
Iteration   3: 5.073 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.977 ±(99.9%) 1.531 ms/op [Average]
  (min, avg, max) = (4.925, 4.977, 5.073), stdev = 0.084
  CI (99.9%): [3.446, 6.508] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 13.945 ±(99.9%) 0.223 ms/op
# Warmup Iteration   2: 5.072 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.491 ±(99.9%) 0.020 ms/op
Iteration   1: 4.345 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.739 ms/op
                 createUser·p0.50:   4.108 ms/op
                 createUser·p0.90:   5.145 ms/op
                 createUser·p0.95:   6.013 ms/op
                 createUser·p0.99:   8.450 ms/op
                 createUser·p0.999:  23.835 ms/op
                 createUser·p0.9999: 26.387 ms/op
                 createUser·p1.00:   27.361 ms/op

Iteration   2: 4.147 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.282 ms/op
                 createUser·p0.50:   3.953 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.136 ms/op
                 createUser·p0.99:   7.807 ms/op
                 createUser·p0.999:  13.483 ms/op
                 createUser·p0.9999: 27.872 ms/op
                 createUser·p1.00:   29.458 ms/op

Iteration   3: 4.319 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   1.823 ms/op
                 createUser·p0.50:   4.055 ms/op
                 createUser·p0.90:   5.120 ms/op
                 createUser·p0.95:   5.734 ms/op
                 createUser·p0.99:   8.102 ms/op
                 createUser·p0.999:  28.082 ms/op
                 createUser·p0.9999: 41.130 ms/op
                 createUser·p1.00:   42.533 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 224773
  mean =      4.268 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 202465 
    [ 5.000, 10.000) = 21184 
    [10.000, 15.000) = 813 
    [15.000, 20.000) = 39 
    [20.000, 25.000) = 87 
    [25.000, 30.000) = 118 
    [30.000, 35.000) = 18 
    [35.000, 40.000) = 26 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.282 ms/op
     p(50.0000) =      4.047 ms/op
     p(90.0000) =      4.997 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      8.159 ms/op
     p(99.9000) =     24.026 ms/op
     p(99.9900) =     40.108 ms/op
     p(99.9990) =     41.796 ms/op
     p(99.9999) =     42.533 ms/op
    p(100.0000) =     42.533 ms/op


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
# Warmup Iteration   1: 12.521 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 4.750 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.058 ±(99.9%) 0.011 ms/op
Iteration   1: 4.169 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.960 ms/op
                 existUser·p0.50:   3.936 ms/op
                 existUser·p0.90:   5.030 ms/op
                 existUser·p0.95:   5.784 ms/op
                 existUser·p0.99:   7.586 ms/op
                 existUser·p0.999:  11.370 ms/op
                 existUser·p0.9999: 25.362 ms/op
                 existUser·p1.00:   26.116 ms/op

Iteration   2: 4.078 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.085 ms/op
                 existUser·p0.50:   3.899 ms/op
                 existUser·p0.90:   4.768 ms/op
                 existUser·p0.95:   5.439 ms/op
                 existUser·p0.99:   7.438 ms/op
                 existUser·p0.999:  24.003 ms/op
                 existUser·p0.9999: 32.866 ms/op
                 existUser·p1.00:   35.258 ms/op

Iteration   3: 4.093 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.700 ms/op
                 existUser·p0.50:   3.920 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   5.333 ms/op
                 existUser·p0.99:   7.832 ms/op
                 existUser·p0.999:  13.003 ms/op
                 existUser·p0.9999: 27.629 ms/op
                 existUser·p1.00:   28.770 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 233382
  mean =      4.113 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 263 
    [ 2.500,  5.000) = 214343 
    [ 5.000,  7.500) = 15787 
    [ 7.500, 10.000) = 2361 
    [10.000, 12.500) = 338 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 34 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.700 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      4.801 ms/op
     p(95.0000) =      5.513 ms/op
     p(99.0000) =      7.700 ms/op
     p(99.9000) =     13.262 ms/op
     p(99.9900) =     31.206 ms/op
     p(99.9990) =     34.024 ms/op
     p(99.9999) =     35.258 ms/op
    p(100.0000) =     35.258 ms/op


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
# Warmup Iteration   1: 13.903 ±(99.9%) 0.182 ms/op
# Warmup Iteration   2: 5.031 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.482 ±(99.9%) 0.014 ms/op
Iteration   1: 4.417 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.298 ms/op
                 getUser·p0.50:   4.141 ms/op
                 getUser·p0.90:   5.112 ms/op
                 getUser·p0.95:   5.964 ms/op
                 getUser·p0.99:   9.961 ms/op
                 getUser·p0.999:  23.708 ms/op
                 getUser·p0.9999: 26.919 ms/op
                 getUser·p1.00:   27.427 ms/op

Iteration   2: 4.429 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.882 ms/op
                 getUser·p0.50:   4.243 ms/op
                 getUser·p0.90:   5.153 ms/op
                 getUser·p0.95:   5.505 ms/op
                 getUser·p0.99:   7.528 ms/op
                 getUser·p0.999:  13.435 ms/op
                 getUser·p0.9999: 28.009 ms/op
                 getUser·p1.00:   28.574 ms/op

Iteration   3: 4.453 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.054 ms/op
                 getUser·p0.50:   4.211 ms/op
                 getUser·p0.90:   5.210 ms/op
                 getUser·p0.95:   6.201 ms/op
                 getUser·p0.99:   8.552 ms/op
                 getUser·p0.999:  27.813 ms/op
                 getUser·p0.9999: 33.456 ms/op
                 getUser·p1.00:   35.848 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 216561
  mean =      4.433 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 41 
    [ 2.500,  5.000) = 188253 
    [ 5.000,  7.500) = 24248 
    [ 7.500, 10.000) = 2648 
    [10.000, 12.500) = 823 
    [12.500, 15.000) = 285 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 111 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.882 ms/op
     p(50.0000) =      4.190 ms/op
     p(90.0000) =      5.161 ms/op
     p(95.0000) =      5.808 ms/op
     p(99.0000) =      8.765 ms/op
     p(99.9000) =     24.164 ms/op
     p(99.9900) =     32.354 ms/op
     p(99.9990) =     34.593 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


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
# Warmup Iteration   1: 14.834 ±(99.9%) 0.251 ms/op
# Warmup Iteration   2: 5.865 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 5.128 ±(99.9%) 0.019 ms/op
Iteration   1: 4.943 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.019 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   5.915 ms/op
                 listUser·p0.99:   9.421 ms/op
                 listUser·p0.999:  27.634 ms/op
                 listUser·p0.9999: 34.275 ms/op
                 listUser·p1.00:   36.110 ms/op

Iteration   2: 4.986 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.630 ms/op
                 listUser·p0.50:   4.751 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   6.595 ms/op
                 listUser·p0.99:   9.667 ms/op
                 listUser·p0.999:  18.481 ms/op
                 listUser·p0.9999: 23.911 ms/op
                 listUser·p1.00:   24.642 ms/op

Iteration   3: 5.021 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.534 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   5.734 ms/op
                 listUser·p0.95:   6.275 ms/op
                 listUser·p0.99:   9.781 ms/op
                 listUser·p0.999:  19.176 ms/op
                 listUser·p0.9999: 24.715 ms/op
                 listUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 192584
  mean =      4.983 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 135850 
    [ 5.000,  7.500) = 50518 
    [ 7.500, 10.000) = 4583 
    [10.000, 12.500) = 863 
    [12.500, 15.000) = 247 
    [15.000, 17.500) = 202 
    [17.500, 20.000) = 91 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 92 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 24 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 28 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.534 ms/op
     p(50.0000) =      4.760 ms/op
     p(90.0000) =      5.513 ms/op
     p(95.0000) =      6.267 ms/op
     p(99.0000) =      9.650 ms/op
     p(99.9000) =     21.329 ms/op
     p(99.9900) =     33.554 ms/op
     p(99.9990) =     36.110 ms/op
     p(99.9999) =     36.110 ms/op
    p(100.0000) =     36.110 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.299 ± 3.158  ops/ms
ClientPb.existUser                       thrpt       3   8.109 ± 1.748  ops/ms
ClientPb.getUser                         thrpt       3   7.589 ± 2.290  ops/ms
ClientPb.listUser                        thrpt       3   6.501 ± 3.389  ops/ms
ClientPb.createUser                       avgt       3   4.194 ± 1.244   ms/op
ClientPb.existUser                        avgt       3   3.999 ± 1.051   ms/op
ClientPb.getUser                          avgt       3   4.161 ± 1.545   ms/op
ClientPb.listUser                         avgt       3   4.977 ± 1.531   ms/op
ClientPb.createUser                     sample  224773   4.268 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.282           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.047           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.997           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.693           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.159           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.026           ms/op
ClientPb.createUser:createUser·p0.9999  sample          40.108           ms/op
ClientPb.createUser:createUser·p1.00    sample          42.533           ms/op
ClientPb.existUser                      sample  233382   4.113 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.700           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.916           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.801           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.513           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.700           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.262           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.206           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.258           ms/op
ClientPb.getUser                        sample  216561   4.433 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.882           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.190           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.161           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.808           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.765           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.164           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.354           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.848           ms/op
ClientPb.listUser                       sample  192584   4.983 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.534           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.760           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.513           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.267           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.650           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.329           ms/op
ClientPb.listUser:listUser·p0.9999      sample          33.554           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.110           ms/op
