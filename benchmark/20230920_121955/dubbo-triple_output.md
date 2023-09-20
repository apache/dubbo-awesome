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
# Warmup Iteration   1: 1.444 ops/ms
# Warmup Iteration   2: 3.028 ops/ms
# Warmup Iteration   3: 6.639 ops/ms
Iteration   1: 7.142 ops/ms
Iteration   2: 7.448 ops/ms
Iteration   3: 7.550 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.380 ±(99.9%) 3.883 ops/ms [Average]
  (min, avg, max) = (7.142, 7.380, 7.550), stdev = 0.213
  CI (99.9%): [3.497, 11.264] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 1.734 ops/ms
# Warmup Iteration   2: 6.050 ops/ms
# Warmup Iteration   3: 7.845 ops/ms
Iteration   1: 7.962 ops/ms
Iteration   2: 8.053 ops/ms
Iteration   3: 7.933 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.983 ±(99.9%) 1.146 ops/ms [Average]
  (min, avg, max) = (7.933, 7.983, 8.053), stdev = 0.063
  CI (99.9%): [6.837, 9.129] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.839 ops/ms
# Warmup Iteration   2: 5.985 ops/ms
# Warmup Iteration   3: 7.349 ops/ms
Iteration   1: 7.318 ops/ms
Iteration   2: 7.400 ops/ms
Iteration   3: 7.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.435 ±(99.9%) 2.518 ops/ms [Average]
  (min, avg, max) = (7.318, 7.435, 7.587), stdev = 0.138
  CI (99.9%): [4.917, 9.952] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.853 ops/ms
# Warmup Iteration   2: 5.302 ops/ms
# Warmup Iteration   3: 6.391 ops/ms
Iteration   1: 6.492 ops/ms
Iteration   2: 6.334 ops/ms
Iteration   3: 6.601 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.476 ±(99.9%) 2.452 ops/ms [Average]
  (min, avg, max) = (6.334, 6.476, 6.601), stdev = 0.134
  CI (99.9%): [4.024, 8.927] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 14.052 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 5.228 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.282 ±(99.9%) 0.006 ms/op
Iteration   1: 4.022 ±(99.9%) 0.008 ms/op
Iteration   2: 4.033 ±(99.9%) 0.005 ms/op
Iteration   3: 4.305 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.120 ±(99.9%) 2.927 ms/op [Average]
  (min, avg, max) = (4.022, 4.120, 4.305), stdev = 0.160
  CI (99.9%): [1.193, 7.047] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 14.087 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.602 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.013 ±(99.9%) 0.007 ms/op
Iteration   1: 3.942 ±(99.9%) 0.008 ms/op
Iteration   2: 3.966 ±(99.9%) 0.004 ms/op
Iteration   3: 4.035 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.981 ±(99.9%) 0.879 ms/op [Average]
  (min, avg, max) = (3.942, 3.981, 4.035), stdev = 0.048
  CI (99.9%): [3.102, 4.860] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 13.898 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.656 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.071 ±(99.9%) 0.004 ms/op
Iteration   1: 4.157 ±(99.9%) 0.009 ms/op
Iteration   2: 4.177 ±(99.9%) 0.006 ms/op
Iteration   3: 4.176 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.170 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (4.157, 4.170, 4.177), stdev = 0.011
  CI (99.9%): [3.963, 4.377] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 14.092 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.615 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.962 ±(99.9%) 0.008 ms/op
Iteration   1: 4.898 ±(99.9%) 0.010 ms/op
Iteration   2: 4.944 ±(99.9%) 0.009 ms/op
Iteration   3: 4.859 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.900 ±(99.9%) 0.777 ms/op [Average]
  (min, avg, max) = (4.859, 4.900, 4.944), stdev = 0.043
  CI (99.9%): [4.123, 5.677] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 13.981 ±(99.9%) 0.232 ms/op
# Warmup Iteration   2: 5.064 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.569 ±(99.9%) 0.020 ms/op
Iteration   1: 4.194 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   2.056 ms/op
                 createUser·p0.50:   3.990 ms/op
                 createUser·p0.90:   4.719 ms/op
                 createUser·p0.95:   5.399 ms/op
                 createUser·p0.99:   8.946 ms/op
                 createUser·p0.999:  24.829 ms/op
                 createUser·p0.9999: 27.361 ms/op
                 createUser·p1.00:   31.982 ms/op

Iteration   2: 4.265 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.554 ms/op
                 createUser·p0.50:   4.067 ms/op
                 createUser·p0.90:   4.915 ms/op
                 createUser·p0.95:   5.407 ms/op
                 createUser·p0.99:   8.487 ms/op
                 createUser·p0.999:  18.252 ms/op
                 createUser·p0.9999: 28.312 ms/op
                 createUser·p1.00:   28.901 ms/op

Iteration   3: 4.272 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.978 ms/op
                 createUser·p0.50:   4.010 ms/op
                 createUser·p0.90:   4.899 ms/op
                 createUser·p0.95:   5.439 ms/op
                 createUser·p0.99:   9.110 ms/op
                 createUser·p0.999:  28.508 ms/op
                 createUser·p0.9999: 30.753 ms/op
                 createUser·p1.00:   31.719 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 226068
  mean =      4.243 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 273 
    [ 2.500,  5.000) = 207869 
    [ 5.000,  7.500) = 13353 
    [ 7.500, 10.000) = 3450 
    [10.000, 12.500) = 641 
    [12.500, 15.000) = 77 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 94 
    [27.500, 30.000) = 102 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.554 ms/op
     p(50.0000) =      4.022 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      8.798 ms/op
     p(99.9000) =     25.098 ms/op
     p(99.9900) =     30.291 ms/op
     p(99.9990) =     31.744 ms/op
     p(99.9999) =     31.982 ms/op
    p(100.0000) =     31.982 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 13.472 ±(99.9%) 0.190 ms/op
# Warmup Iteration   2: 5.060 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.013 ms/op
Iteration   1: 4.075 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.790 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.653 ms/op
                 existUser·p0.95:   5.784 ms/op
                 existUser·p0.99:   8.798 ms/op
                 existUser·p0.999:  16.211 ms/op
                 existUser·p0.9999: 27.578 ms/op
                 existUser·p1.00:   29.491 ms/op

Iteration   2: 4.087 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.561 ms/op
                 existUser·p0.50:   3.830 ms/op
                 existUser·p0.90:   4.645 ms/op
                 existUser·p0.95:   5.104 ms/op
                 existUser·p0.99:   8.487 ms/op
                 existUser·p0.999:  26.018 ms/op
                 existUser·p0.9999: 38.111 ms/op
                 existUser·p1.00:   41.550 ms/op

Iteration   3: 4.046 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.059 ms/op
                 existUser·p0.50:   3.838 ms/op
                 existUser·p0.90:   4.579 ms/op
                 existUser·p0.95:   5.186 ms/op
                 existUser·p0.99:   8.520 ms/op
                 existUser·p0.999:  21.885 ms/op
                 existUser·p0.9999: 30.546 ms/op
                 existUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 235828
  mean =      4.069 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 220861 
    [ 5.000, 10.000) = 13837 
    [10.000, 15.000) = 607 
    [15.000, 20.000) = 110 
    [20.000, 25.000) = 183 
    [25.000, 30.000) = 191 
    [30.000, 35.000) = 22 
    [35.000, 40.000) = 14 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      3.834 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.251 ms/op
     p(99.0000) =      8.634 ms/op
     p(99.9000) =     24.904 ms/op
     p(99.9900) =     30.824 ms/op
     p(99.9990) =     41.419 ms/op
     p(99.9999) =     41.550 ms/op
    p(100.0000) =     41.550 ms/op


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
# Warmup Iteration   1: 14.123 ±(99.9%) 0.216 ms/op
# Warmup Iteration   2: 4.763 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.403 ±(99.9%) 0.016 ms/op
Iteration   1: 4.086 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.175 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   4.497 ms/op
                 getUser·p0.95:   4.825 ms/op
                 getUser·p0.99:   7.881 ms/op
                 getUser·p0.999:  23.790 ms/op
                 getUser·p0.9999: 27.203 ms/op
                 getUser·p1.00:   27.820 ms/op

Iteration   2: 4.126 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   2.068 ms/op
                 getUser·p0.50:   3.912 ms/op
                 getUser·p0.90:   4.612 ms/op
                 getUser·p0.95:   5.079 ms/op
                 getUser·p0.99:   8.585 ms/op
                 getUser·p0.999:  19.531 ms/op
                 getUser·p0.9999: 28.025 ms/op
                 getUser·p1.00:   28.279 ms/op

Iteration   3: 4.090 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.454 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.579 ms/op
                 getUser·p0.95:   5.292 ms/op
                 getUser·p0.99:   8.503 ms/op
                 getUser·p0.999:  16.191 ms/op
                 getUser·p0.9999: 42.873 ms/op
                 getUser·p1.00:   44.433 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234030
  mean =      4.101 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 221784 
    [ 5.000, 10.000) = 11296 
    [10.000, 15.000) = 640 
    [15.000, 20.000) = 70 
    [20.000, 25.000) = 63 
    [25.000, 30.000) = 145 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 12 
    [40.000, 45.000) = 20 

  Percentiles, ms/op:
      p(0.0000) =      2.068 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      5.054 ms/op
     p(99.0000) =      8.380 ms/op
     p(99.9000) =     20.315 ms/op
     p(99.9900) =     39.399 ms/op
     p(99.9990) =     43.947 ms/op
     p(99.9999) =     44.433 ms/op
    p(100.0000) =     44.433 ms/op


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
# Warmup Iteration   1: 14.676 ±(99.9%) 0.211 ms/op
# Warmup Iteration   2: 6.157 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.183 ±(99.9%) 0.021 ms/op
Iteration   1: 5.072 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.851 ms/op
                 listUser·p0.50:   4.841 ms/op
                 listUser·p0.90:   5.513 ms/op
                 listUser·p0.95:   6.341 ms/op
                 listUser·p0.99:   10.387 ms/op
                 listUser·p0.999:  27.886 ms/op
                 listUser·p0.9999: 29.645 ms/op
                 listUser·p1.00:   30.310 ms/op

Iteration   2: 5.133 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   2.380 ms/op
                 listUser·p0.50:   4.907 ms/op
                 listUser·p0.90:   5.628 ms/op
                 listUser·p0.95:   6.500 ms/op
                 listUser·p0.99:   10.895 ms/op
                 listUser·p0.999:  21.078 ms/op
                 listUser·p0.9999: 24.642 ms/op
                 listUser·p1.00:   25.002 ms/op

Iteration   3: 4.952 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.321 ms/op
                 listUser·p0.50:   4.694 ms/op
                 listUser·p0.90:   5.571 ms/op
                 listUser·p0.95:   5.980 ms/op
                 listUser·p0.99:   9.306 ms/op
                 listUser·p0.999:  17.629 ms/op
                 listUser·p0.9999: 20.301 ms/op
                 listUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 189963
  mean =      5.051 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 118554 
    [ 5.000,  7.500) = 64844 
    [ 7.500, 10.000) = 4251 
    [10.000, 12.500) = 1419 
    [12.500, 15.000) = 295 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 127 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 48 
    [27.500, 30.000) = 88 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      4.833 ms/op
     p(90.0000) =      5.579 ms/op
     p(95.0000) =      6.210 ms/op
     p(99.0000) =     10.289 ms/op
     p(99.9000) =     22.644 ms/op
     p(99.9900) =     29.000 ms/op
     p(99.9990) =     30.222 ms/op
     p(99.9999) =     30.310 ms/op
    p(100.0000) =     30.310 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.380 ± 3.883  ops/ms
ClientPb.existUser                       thrpt       3   7.983 ± 1.146  ops/ms
ClientPb.getUser                         thrpt       3   7.435 ± 2.518  ops/ms
ClientPb.listUser                        thrpt       3   6.476 ± 2.452  ops/ms
ClientPb.createUser                       avgt       3   4.120 ± 2.927   ms/op
ClientPb.existUser                        avgt       3   3.981 ± 0.879   ms/op
ClientPb.getUser                          avgt       3   4.170 ± 0.207   ms/op
ClientPb.listUser                         avgt       3   4.900 ± 0.777   ms/op
ClientPb.createUser                     sample  226068   4.243 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.554           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.022           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.850           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.415           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.798           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.098           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.291           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.982           ms/op
ClientPb.existUser                      sample  235828   4.069 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.059           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.834           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.628           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.251           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.634           ms/op
ClientPb.existUser:existUser·p0.999     sample          24.904           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.824           ms/op
ClientPb.existUser:existUser·p1.00      sample          41.550           ms/op
ClientPb.getUser                        sample  234030   4.101 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.068           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.563           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.054           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.380           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.315           ms/op
ClientPb.getUser:getUser·p0.9999        sample          39.399           ms/op
ClientPb.getUser:getUser·p1.00          sample          44.433           ms/op
ClientPb.listUser                       sample  189963   5.051 ± 0.010   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.321           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.833           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.210           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.289           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.644           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.000           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.310           ms/op
