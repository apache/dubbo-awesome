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
# Warmup Iteration   1: 1.097 ops/ms
# Warmup Iteration   2: 2.370 ops/ms
# Warmup Iteration   3: 4.911 ops/ms
Iteration   1: 5.486 ops/ms
Iteration   2: 5.645 ops/ms
Iteration   3: 5.929 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.687 ±(99.9%) 4.089 ops/ms [Average]
  (min, avg, max) = (5.486, 5.687, 5.929), stdev = 0.224
  CI (99.9%): [1.598, 9.776] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.757 ops/ms
# Warmup Iteration   2: 5.050 ops/ms
# Warmup Iteration   3: 5.763 ops/ms
Iteration   1: 6.416 ops/ms
Iteration   2: 6.258 ops/ms
Iteration   3: 6.388 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.354 ±(99.9%) 1.541 ops/ms [Average]
  (min, avg, max) = (6.258, 6.354, 6.416), stdev = 0.084
  CI (99.9%): [4.813, 7.895] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.579 ops/ms
# Warmup Iteration   2: 4.324 ops/ms
# Warmup Iteration   3: 5.611 ops/ms
Iteration   1: 5.525 ops/ms
Iteration   2: 5.566 ops/ms
Iteration   3: 6.026 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.706 ±(99.9%) 5.082 ops/ms [Average]
  (min, avg, max) = (5.525, 5.706, 6.026), stdev = 0.279
  CI (99.9%): [0.624, 10.787] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 1.363 ops/ms
# Warmup Iteration   2: 3.976 ops/ms
# Warmup Iteration   3: 4.981 ops/ms
Iteration   1: 4.994 ops/ms
Iteration   2: 4.969 ops/ms
Iteration   3: 5.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.003 ±(99.9%) 0.706 ops/ms [Average]
  (min, avg, max) = (4.969, 5.003, 5.045), stdev = 0.039
  CI (99.9%): [4.297, 5.709] (assumes normal distribution)


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
# Warmup Iteration   1: 18.284 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 7.527 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.638 ±(99.9%) 0.019 ms/op
Iteration   1: 5.481 ±(99.9%) 0.017 ms/op
Iteration   2: 5.413 ±(99.9%) 0.018 ms/op
Iteration   3: 5.258 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.384 ±(99.9%) 2.084 ms/op [Average]
  (min, avg, max) = (5.258, 5.384, 5.481), stdev = 0.114
  CI (99.9%): [3.299, 7.468] (assumes normal distribution)


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
# Warmup Iteration   1: 17.223 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 5.972 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.507 ±(99.9%) 0.008 ms/op
Iteration   1: 5.289 ±(99.9%) 0.009 ms/op
Iteration   2: 5.137 ±(99.9%) 0.012 ms/op
Iteration   3: 5.099 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.175 ±(99.9%) 1.836 ms/op [Average]
  (min, avg, max) = (5.099, 5.175, 5.289), stdev = 0.101
  CI (99.9%): [3.339, 7.011] (assumes normal distribution)


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
# Warmup Iteration   1: 18.531 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.313 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.711 ±(99.9%) 0.010 ms/op
Iteration   1: 5.580 ±(99.9%) 0.007 ms/op
Iteration   2: 5.533 ±(99.9%) 0.019 ms/op
Iteration   3: 5.641 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.585 ±(99.9%) 0.983 ms/op [Average]
  (min, avg, max) = (5.533, 5.585, 5.641), stdev = 0.054
  CI (99.9%): [4.602, 6.568] (assumes normal distribution)


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
# Warmup Iteration   1: 18.223 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 8.062 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 6.553 ±(99.9%) 0.008 ms/op
Iteration   1: 6.380 ±(99.9%) 0.014 ms/op
Iteration   2: 6.293 ±(99.9%) 0.019 ms/op
Iteration   3: 6.300 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.324 ±(99.9%) 0.883 ms/op [Average]
  (min, avg, max) = (6.293, 6.324, 6.380), stdev = 0.048
  CI (99.9%): [5.441, 7.207] (assumes normal distribution)


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
# Warmup Iteration   1: 17.290 ±(99.9%) 0.272 ms/op
# Warmup Iteration   2: 6.601 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 6.248 ±(99.9%) 0.029 ms/op
Iteration   1: 5.528 ±(99.9%) 0.018 ms/op
                 createUser·p0.00:   2.515 ms/op
                 createUser·p0.50:   5.272 ms/op
                 createUser·p0.90:   6.685 ms/op
                 createUser·p0.95:   7.471 ms/op
                 createUser·p0.99:   9.535 ms/op
                 createUser·p0.999:  23.402 ms/op
                 createUser·p0.9999: 28.948 ms/op
                 createUser·p1.00:   30.409 ms/op

Iteration   2: 5.371 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.331 ms/op
                 createUser·p0.50:   5.087 ms/op
                 createUser·p0.90:   6.390 ms/op
                 createUser·p0.95:   7.103 ms/op
                 createUser·p0.99:   10.863 ms/op
                 createUser·p0.999:  25.180 ms/op
                 createUser·p0.9999: 28.804 ms/op
                 createUser·p1.00:   29.295 ms/op

Iteration   3: 5.569 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.306 ms/op
                 createUser·p0.50:   5.349 ms/op
                 createUser·p0.90:   6.808 ms/op
                 createUser·p0.95:   7.422 ms/op
                 createUser·p0.99:   9.585 ms/op
                 createUser·p0.999:  26.941 ms/op
                 createUser·p0.9999: 32.997 ms/op
                 createUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 174869
  mean =      5.488 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 64049 
    [ 5.000,  7.500) = 102867 
    [ 7.500, 10.000) = 6270 
    [10.000, 12.500) = 1055 
    [12.500, 15.000) = 278 
    [15.000, 17.500) = 120 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.306 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      6.644 ms/op
     p(95.0000) =      7.365 ms/op
     p(99.0000) =      9.912 ms/op
     p(99.9000) =     24.908 ms/op
     p(99.9900) =     32.295 ms/op
     p(99.9990) =     35.488 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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
# Warmup Iteration   1: 17.324 ±(99.9%) 0.247 ms/op
# Warmup Iteration   2: 6.485 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 5.382 ±(99.9%) 0.019 ms/op
Iteration   1: 5.154 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   2.273 ms/op
                 existUser·p0.50:   4.964 ms/op
                 existUser·p0.90:   6.078 ms/op
                 existUser·p0.95:   6.783 ms/op
                 existUser·p0.99:   8.716 ms/op
                 existUser·p0.999:  21.592 ms/op
                 existUser·p0.9999: 26.240 ms/op
                 existUser·p1.00:   27.460 ms/op

Iteration   2: 5.347 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.241 ms/op
                 existUser·p0.50:   5.104 ms/op
                 existUser·p0.90:   6.423 ms/op
                 existUser·p0.95:   7.045 ms/op
                 existUser·p0.99:   9.830 ms/op
                 existUser·p0.999:  15.672 ms/op
                 existUser·p0.9999: 29.001 ms/op
                 existUser·p1.00:   30.736 ms/op

Iteration   3: 5.557 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.327 ms/op
                 existUser·p0.50:   5.308 ms/op
                 existUser·p0.90:   6.775 ms/op
                 existUser·p0.95:   7.504 ms/op
                 existUser·p0.99:   9.585 ms/op
                 existUser·p0.999:  27.899 ms/op
                 existUser·p0.9999: 36.517 ms/op
                 existUser·p1.00:   38.404 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 179586
  mean =      5.347 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 78397 
    [ 5.000,  7.500) = 94158 
    [ 7.500, 10.000) = 5699 
    [10.000, 12.500) = 876 
    [12.500, 15.000) = 219 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      2.241 ms/op
     p(50.0000) =      5.104 ms/op
     p(90.0000) =      6.447 ms/op
     p(95.0000) =      7.176 ms/op
     p(99.0000) =      9.454 ms/op
     p(99.9000) =     16.077 ms/op
     p(99.9900) =     32.771 ms/op
     p(99.9990) =     37.413 ms/op
     p(99.9999) =     38.404 ms/op
    p(100.0000) =     38.404 ms/op


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
# Warmup Iteration   1: 19.147 ±(99.9%) 0.365 ms/op
# Warmup Iteration   2: 7.356 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 5.782 ±(99.9%) 0.019 ms/op
Iteration   1: 5.594 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.892 ms/op
                 getUser·p0.50:   5.399 ms/op
                 getUser·p0.90:   6.513 ms/op
                 getUser·p0.95:   7.193 ms/op
                 getUser·p0.99:   10.338 ms/op
                 getUser·p0.999:  15.134 ms/op
                 getUser·p0.9999: 26.982 ms/op
                 getUser·p1.00:   29.065 ms/op

Iteration   2: 5.719 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.241 ms/op
                 getUser·p0.50:   5.390 ms/op
                 getUser·p0.90:   7.045 ms/op
                 getUser·p0.95:   7.766 ms/op
                 getUser·p0.99:   9.905 ms/op
                 getUser·p0.999:  28.313 ms/op
                 getUser·p0.9999: 33.778 ms/op
                 getUser·p1.00:   34.275 ms/op

Iteration   3: 5.859 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.355 ms/op
                 getUser·p0.50:   5.587 ms/op
                 getUser·p0.90:   7.135 ms/op
                 getUser·p0.95:   7.889 ms/op
                 getUser·p0.99:   10.633 ms/op
                 getUser·p0.999:  31.013 ms/op
                 getUser·p0.9999: 35.687 ms/op
                 getUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 167657
  mean =      5.722 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 40971 
    [ 5.000,  7.500) = 116875 
    [ 7.500, 10.000) = 7853 
    [10.000, 12.500) = 1451 
    [12.500, 15.000) = 204 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 14 
    [27.500, 30.000) = 20 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 45 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.241 ms/op
     p(50.0000) =      5.448 ms/op
     p(90.0000) =      6.930 ms/op
     p(95.0000) =      7.676 ms/op
     p(99.0000) =     10.338 ms/op
     p(99.9000) =     22.970 ms/op
     p(99.9900) =     33.897 ms/op
     p(99.9990) =     36.478 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


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
# Warmup Iteration   1: 19.337 ±(99.9%) 0.350 ms/op
# Warmup Iteration   2: 8.498 ±(99.9%) 0.071 ms/op
# Warmup Iteration   3: 6.930 ±(99.9%) 0.033 ms/op
Iteration   1: 6.585 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.441 ms/op
                 listUser·p0.50:   6.201 ms/op
                 listUser·p0.90:   7.799 ms/op
                 listUser·p0.95:   9.306 ms/op
                 listUser·p0.99:   13.058 ms/op
                 listUser·p0.999:  30.667 ms/op
                 listUser·p0.9999: 39.069 ms/op
                 listUser·p1.00:   42.140 ms/op

Iteration   2: 6.410 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.867 ms/op
                 listUser·p0.50:   6.152 ms/op
                 listUser·p0.90:   7.406 ms/op
                 listUser·p0.95:   8.176 ms/op
                 listUser·p0.99:   10.977 ms/op
                 listUser·p0.999:  30.318 ms/op
                 listUser·p0.9999: 32.775 ms/op
                 listUser·p1.00:   33.948 ms/op

Iteration   3: 6.604 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.556 ms/op
                 listUser·p0.50:   6.193 ms/op
                 listUser·p0.90:   7.995 ms/op
                 listUser·p0.95:   9.388 ms/op
                 listUser·p0.99:   12.616 ms/op
                 listUser·p0.999:  25.910 ms/op
                 listUser·p0.9999: 30.899 ms/op
                 listUser·p1.00:   32.834 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 146774
  mean =      6.532 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3025 
    [ 5.000, 10.000) = 139301 
    [10.000, 15.000) = 3853 
    [15.000, 20.000) = 274 
    [20.000, 25.000) = 68 
    [25.000, 30.000) = 130 
    [30.000, 35.000) = 98 
    [35.000, 40.000) = 23 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.441 ms/op
     p(50.0000) =      6.185 ms/op
     p(90.0000) =      7.717 ms/op
     p(95.0000) =      8.897 ms/op
     p(99.0000) =     12.468 ms/op
     p(99.9000) =     29.138 ms/op
     p(99.9900) =     37.093 ms/op
     p(99.9990) =     42.048 ms/op
     p(99.9999) =     42.140 ms/op
    p(100.0000) =     42.140 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.687 ± 4.089  ops/ms
ClientPb.existUser                       thrpt       3   6.354 ± 1.541  ops/ms
ClientPb.getUser                         thrpt       3   5.706 ± 5.082  ops/ms
ClientPb.listUser                        thrpt       3   5.003 ± 0.706  ops/ms
ClientPb.createUser                       avgt       3   5.384 ± 2.084   ms/op
ClientPb.existUser                        avgt       3   5.175 ± 1.836   ms/op
ClientPb.getUser                          avgt       3   5.585 ± 0.983   ms/op
ClientPb.listUser                         avgt       3   6.324 ± 0.883   ms/op
ClientPb.createUser                     sample  174869   5.488 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.306           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.218           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.644           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.365           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.912           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.908           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.295           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.783           ms/op
ClientPb.existUser                      sample  179586   5.347 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.241           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.104           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.447           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.176           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.454           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.077           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.771           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.404           ms/op
ClientPb.getUser                        sample  167657   5.722 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.241           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.448           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.930           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.676           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.338           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.970           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.897           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.700           ms/op
ClientPb.listUser                       sample  146774   6.532 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.441           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.185           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.717           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.897           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.468           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.138           ms/op
ClientPb.listUser:listUser·p0.9999      sample          37.093           ms/op
ClientPb.listUser:listUser·p1.00        sample          42.140           ms/op
